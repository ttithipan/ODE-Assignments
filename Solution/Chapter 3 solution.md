# Chapter 3 Solutions

## Assignment 1: Laplace Transforms by Definition
Definition of Laplace Transform: $\mathcal{L}\{f(t)\} = \int_{0}^{\infty} e^{-st} f(t) dt$

**1. $f(t) = t$**

> Solution:
> $$\mathcal{L}\{t\} = \int_{0}^{\infty} e^{-st} t dt$$
> Using integration by parts: Let $u=t \implies du=dt$, and $dv = e^{-st}dt \implies v = -\frac{1}{s}e^{-st}$.
> $$\mathcal{L}\{t\} = \left[ -\frac{t}{s}e^{-st} \right]_0^\infty + \int_{0}^{\infty} \frac{1}{s}e^{-st} dt = 0 + \left[ -\frac{1}{s^2}e^{-st} \right]_0^\infty = \frac{1}{s^2} \quad (s > 0)$$
>
**2. $f(t) = t^2$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{t^2\} = \int_{0}^{\infty} e^{-st} t^2 dt$$
> Using integration by parts: Let $u=t^2 \implies du=2tdt$, and $dv = e^{-st}dt \implies v = -\frac{1}{s}e^{-st}$.
> $$\mathcal{L}\{t^2\} = \left[ -\frac{t^2}{s}e^{-st} \right]_0^\infty + \frac{2}{s}\int_{0}^{\infty} t e^{-st} dt = 0 + \frac{2}{s} \mathcal{L}\{t\} = \frac{2}{s} \cdot \frac{1}{s^2} = \frac{2}{s^3} \quad (s > 0)$$
>
**3. $f(t) = e^{3t+1}$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{e^{3t+1}\} = \int_{0}^{\infty} e^{-st} e^{3t} \cdot e^1 dt = e \int_{0}^{\infty} e^{-(s-3)t} dt$$
> $$\mathcal{L}\{e^{3t+1}\} = e \left[ \frac{e^{-(s-3)t}}{-(s-3)} \right]_0^\infty = \frac{e}{s-3} \quad (s > 3)$$
>
**4. $f(t) = \cos t$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{\cos t\} = \int_{0}^{\infty} e^{-st} \cos t dt$$
> Using integration by parts twice to evaluate the integral $I = \int e^{-st} \cos t dt$:
> $u = \cos t \implies du = -\sin t dt$, $dv = e^{-st}dt \implies v = -\frac{1}{s}e^{-st}$
> $$I = -\frac{1}{s}e^{-st}\cos t - \frac{1}{s}\int e^{-st} \sin t dt$$
> For the inner integral, parts again: $u = \sin t, dv = e^{-st}dt \implies v = -\frac{1}{s}e^{-st}$
> $$I = -\frac{1}{s}e^{-st}\cos t - \frac{1}{s}\left( -\frac{1}{s}e^{-st}\sin t + \frac{1}{s}\int e^{-st}\cos t dt \right)$$
> $$I = e^{-st}\left(-\frac{1}{s}\cos t + \frac{1}{s^2}\sin t\right) - \frac{1}{s^2} I$$
> $$I \left(1 + \frac{1}{s^2}\right) = e^{-st}\left(-\frac{1}{s}\cos t + \frac{1}{s^2}\sin t\right)$$
> Evaluating from $0$ to$\infty$(assuming$s > 0$):
> $$\mathcal{L}\{\cos t\} \cdot \frac{s^2+1}{s^2} = 0 - \left( -\frac{1}{s} \right) = \frac{1}{s} \implies \mathcal{L}\{\cos t\} = \frac{s}{s^2+1} \quad (s > 0)$$
>
**5. $f(t) = \sinh t$**

> \*\*Solution:\*\*
> $$f(t) = \frac{e^t - e^{-t}}{2}$$
> $$\mathcal{L}\{\sinh t\} = \int_{0}^{\infty} e^{-st} \frac{e^t - e^{-t}}{2} dt = \frac{1}{2} \int_{0}^{\infty} \left( e^{-(s-1)t} - e^{-(s+1)t} \right) dt$$
> $$\mathcal{L}\{\sinh t\} = \frac{1}{2} \left[ \frac{e^{-(s-1)t}}{-(s-1)} - \frac{e^{-(s+1)t}}{-(s+1)} \right]_0^\infty = \frac{1}{2} \left( \frac{1}{s-1} - \frac{1}{s+1} \right) = \frac{1}{2} \left(\frac{s+1 - (s-1)}{s^2-1}\right) = \frac{1}{s^2-1} \quad (s > 1)$$
>
**6. $f(t) = \sin^2 t$**

> \*\*Solution:\*\*
> Using the double angle identity: $\sin^2 t = \frac{1 - \cos 2t}{2}$
> $$\mathcal{L}\{\sin^2 t\} = \frac{1}{2} \int_{0}^{\infty} e^{-st} (1 - \cos 2t) dt$$
> From #4, $\int e^{-st}\cos at dt = \frac{s}{s^2+a^2}$.
> $$\mathcal{L}\{\sin^2 t\} = \frac{1}{2} \left[ \int_{0}^{\infty} e^{-st} dt - \int_{0}^{\infty} e^{-st} \cos 2t dt \right]$$
> $$\mathcal{L}\{\sin^2 t\} = \frac{1}{2} \left( \frac{1}{s} - \frac{s}{s^2+4} \right) = \frac{s^2+4-s^2}{2s(s^2+4)} = \frac{2}{s(s^2+4)} \quad (s > 0)$$
>
## Assignment 2: Standard Laplace Transforms
Using standard Laplace Transform tables and properties.

**1. $f(t) = \sqrt{t} + 3t = t^{1/2} + 3t$**

> \*\*Solution:\*\*
> Using $\mathcal{L}\{t^n\} = \frac{\Gamma(n+1)}{s^{n+1}}$, $\Gamma(3/2) = \frac{\sqrt{\pi}}{2}$.
> $$\mathcal{L}\{f(t)\} = \frac{\Gamma(3/2)}{s^{3/2}} + \frac{3}{s^2} = \frac{\sqrt{\pi}}{2s^{3/2}} + \frac{3}{s^2}$$
>
**2. $f(t) = 3t^{5/2} - 4t^3$**

> \*\*Solution:\*\*
> Using $\Gamma(7/2) = \frac{5}{2}\cdot\frac{3}{2}\cdot\frac{1}{2}\sqrt{\pi} = \frac{15}{8}\sqrt{\pi}$.
> $$\mathcal{L}\{f(t)\} = 3 \frac{\Gamma(7/2)}{s^{7/2}} - 4\frac{3!}{s^4} = 3 \left( \frac{15\sqrt{\pi}}{8s^{7/2}} \right) - \frac{24}{s^4} = \frac{45\sqrt{\pi}}{8s^{7/2}} - \frac{24}{s^4}$$
>
**3. $f(t) = t - 2e^{3t}$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{f(t)\} = \mathcal{L}\{t\} - 2\mathcal{L}\{e^{3t}\} = \frac{1}{s^2} - \frac{2}{s-3}$$
>
**4. $f(t) = t^{3/2} e^{-10t}$**

> \*\*Solution:\*\*
> Using the first shifting theorem: $\mathcal{L}\{e^{at}f(t)\} = F(s-a)$, and $\Gamma(5/2) = \frac{3}{4}\sqrt{\pi}$.
> $$\mathcal{L}\{t^{3/2}\} = \frac{\Gamma(5/2)}{s^{5/2}} = \frac{3\sqrt{\pi}}{4s^{5/2}}$$
> $$\mathcal{L}\{f(t)\} = \frac{3\sqrt{\pi}}{4(s+10)^{5/2}}$$
>
**5. $f(t) = 1 + \cosh(5t)$**

> \*\*Solution:\*\*
> Using the standard identity $\mathcal{L}\{\cosh at\} = \frac{s}{s^2-a^2}$.
> $$\mathcal{L}\{f(t)\} = \frac{1}{s} + \frac{s}{s^2-25}$$
>
**6. $f(t) = \sin(2t) + \cos(2t)$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{f(t)\} = \frac{2}{s^2+4} + \frac{s}{s^2+4} = \frac{s+2}{s^2+4}$$
>
**7. $f(t) = \cos^2(2t)$**

> \*\*Solution:\*\*
> Using half-angle formula: $\cos^2(2t) = \frac{1 + \cos(4t)}{2}$.
> $$\mathcal{L}\{f(t)\} = \frac{1}{2}\mathcal{L}\{1\} + \frac{1}{2}\mathcal{L}\{\cos(4t)\} = \frac{1}{2s} + \frac{s}{2(s^2+16)} = \frac{s^2+16+s^2}{2s(s^2+16)} = \frac{s^2+8}{s(s^2+16)}$$
>
**8. $f(t) = \sin(3t)\cos(3t)$**

> \*\*Solution:\*\*
> Using double-angle formula: $\sin(3t)\cos(3t) = \frac{1}{2}\sin(6t)$.
> $$\mathcal{L}\{f(t)\} = \frac{1}{2} \cdot \frac{6}{s^2+36} = \frac{3}{s^2+36}$$
>
**9. $f(t) = (1+t)^3$**

> \*\*Solution:\*\*
> Expanding the binomial: $(1+t)^3 = 1 + 3t + 3t^2 + t^3$.
> $$\mathcal{L}\{f(t)\} = \frac{1}{s} + \frac{3}{s^2} + 3\left(\frac{2}{s^3}\right) + \frac{6}{s^4} = \frac{1}{s} + \frac{3}{s^2} + \frac{6}{s^3} + \frac{6}{s^4}$$
>
**10. $f(t) = t e^{t}$**

> \*\*Solution:\*\*
> Using first shifting theorem $\mathcal{L}\{e^{at}f(t)\} = F(s-a)$, where $F(s) = \mathcal{L}\{t\} = 1/s^2$.
> $$\mathcal{L}\{f(t)\} = \frac{1}{(s-1)^2}$$
>
**11. $f(t) = t \cos(2t)$**

> \*\*Solution:\*\*
> Using the derivative theorem: $\mathcal{L}\{t f(t)\} = -F'(s)$, where $F(s) = \mathcal{L}\{\cos(2t)\} = \frac{s}{s^2+4}$.
> $$F'(s) = \frac{d}{ds}\left(\frac{s}{s^2+4}\right) = \frac{1(s^2+4) - s(2s)}{(s^2+4)^2} = \frac{4-s^2}{(s^2+4)^2}$$
> $$\mathcal{L}\{f(t)\} = -F'(s) = \frac{s^2-4}{(s^2+4)^2}$$
>
**12. $f(t) = \sinh^2(3t)$**

> \*\*Solution:\*\*
> Using the identity $\sinh^2(3t) = \frac{\cosh(6t) - 1}{2}$.
> $$\mathcal{L}\{f(t)\} = \frac{1}{2} \mathcal{L}\{\cosh(6t)\} - \frac{1}{2}\mathcal{L}\{1\} = \frac{1}{2} \frac{s}{s^2-36} - \frac{1}{2s} = \frac{s^2 - (s^2-36)}{2s(s^2-36)} = \frac{18}{s(s^2-36)}$$
>
>
## Assignment 3: Piecewise/Graphical Functions

**1. A function $f(t)$ defined by a ramp starting at $(0,0)$ and reaching $(1,1)$, then zero for $t > 1$.**

> \*\*Solution:\*\*
> The function is $f(t) = t$ for $0 \le t < 1$, and $0$ for$t \ge 1$.
> $$\mathcal{L}\{f(t)\} = \int_0^1 e^{-st} t dt$$
> Using integration by parts: $u=t \implies du=dt$, $dv=e^{-st}dt \implies v=-\frac{1}{s}e^{-st}$.
> $$\mathcal{L}\{f(t)\} = \left[ -\frac{t}{s}e^{-st} \right]_0^1 + \frac{1}{s} \int_0^1 e^{-st} dt = -\frac{1}{s}e^{-s} - \frac{1}{s^2}e^{-s} + \frac{1}{s^2} = \frac{1 - e^{-s}(1+s)}{s^2}$$
>
**2. A pulse function $f(t)$ that is $1$ on the interval$[1, 2]$and$0$ otherwise.**

> \*\*Solution:\*\*
> $$\mathcal{L}\{f(t)\} = \int_1^2 e^{-st} (1) dt = \left[ -\frac{1}{s}e^{-st} \right]_1^2 = \frac{e^{-s} - e^{-2s}}{s}$$
>
**3. A function $f(t)$ that is a ramp from $(0,0)$ to $(1,1)$ and then stays at $1$ for$t > 1$.**

> \*\*Solution:\*\*
> The function is $f(t) = t$ for $0 \le t < 1$, and $1$ for$t \ge 1$.
> $$\mathcal{L}\{f(t)\} = \int_0^1 e^{-st} t dt + \int_1^\infty e^{-st} dt$$
> From #1, the first integral is $\frac{1 - e^{-s}(1+s)}{s^2}$. The second is $\left[-\frac{1}{s}e^{-st}\right]_1^\infty = \frac{e^{-s}}{s}$.
> $$\mathcal{L}\{f(t)\} = \frac{1 - s e^{-s} - e^{-s} + s e^{-s}}{s^2} = \frac{1 - e^{-s}}{s^2}$$
>
## Assignment 4: Initial-Value Problems

**1. $x''+4x=0; x(0)=5, x'(0)=0$**

> \*\*Solution:\*\*
> Take the Laplace transform of both sides:
> $$s^2 X(s) - s x(0) - x'(0) + 4 X(s) = 0$$
> $$s^2 X(s) - 5s + 4 X(s) = 0 \implies (s^2+4)X(s) = 5s \implies X(s) = \frac{5s}{s^2+4}$$
> Inverse transform: $x(t) = 5\cos(2t)$.
>
**2. $x''+9x=0; x(0)=3, x'(0)=4$**

> \*\*Solution:\*\*
> $$s^2 X(s) - 3s - 4 + 9 X(s) = 0 \implies (s^2+9)X(s) = 3s + 4$$
> $$X(s) = \frac{3s}{s^2+9} + \frac{4}{s^2+9}$$
> Inverse transform: $x(t) = 3\cos(3t) + \frac{4}{3}\sin(3t)$.
>
**3. $x''-x'-2x=0; x(0)=0, x'(0)=2$**

> \*\*Solution:\*\*
> $$(s^2 X(s) - 2) - (s X(s)) - 2 X(s) = 0 \implies (s^2 - s - 2)X(s) = 2$$
> $$X(s) = \frac{2}{(s-2)(s+1)} = \frac{A}{s-2} + \frac{B}{s+1}$$
> $A(s+1) + B(s-2) = 2 \implies 3A = 2 \implies A = 2/3$, and $-3B = 2 \implies B = -2/3$.
> $$X(s) = \frac{2/3}{s-2} - \frac{2/3}{s+1}$$
> Inverse transform: $x(t) = \frac{2}{3}e^{2t} - \frac{2}{3}e^{-t}$.
>
**4. $x''+8x'+15x=0; x(0)=2, x'(0)=3$**

> \*\*Solution:\*\*
> $$(s^2 X(s) - 2s - 3) + 8(s X(s) - 2) + 15 X(s) = 0$$
> $$(s^2 + 8s + 15)X(s) = 2s + 3 + 16 = 2s + 19$$
> $$X(s) = \frac{2s+19}{(s+3)(s+5)} = \frac{A}{s+3} + \frac{B}{s+5}$$
> $A(s+5) + B(s+3) = 2s+19 \implies 2A = 13 \implies A=13/2$, $-2B = 9 \implies B=-9/2$.
> $$X(s) = \frac{13/2}{s+3} - \frac{9/2}{s+5}$$
> Inverse transform: $x(t) = \frac{13}{2}e^{-3t} - \frac{9}{2}e^{-5t}$.
>
**5. $x''+x=\sin 2t; x(0)=0, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2+1)X(s) = \frac{2}{s^2+4} \implies X(s) = \frac{2}{(s^2+1)(s^2+4)}$$
> Using partial fractions: $\frac{2}{(s^2+1)(s^2+4)} = \frac{A}{s^2+1} + \frac{B}{s^2+4}$.
> $A(s^2+4) + B(s^2+1) = 2 \implies 3A = 2 \implies A=2/3$, $-3B = 2 \implies B=-2/3$.
> $$X(s) = \frac{2/3}{s^2+1} - \frac{2/3}{s^2+4} = \frac{2}{3}\frac{1}{s^2+1} - \frac{1}{3}\frac{2}{s^2+4}$$
> Inverse transform: $x(t) = \frac{2}{3}\sin t - \frac{1}{3}\sin 2t$.
>
**6. $x''+4x=\cos t; x(0)=0, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2+4)X(s) = \frac{s}{s^2+1} \implies X(s) = \frac{s}{(s^2+4)(s^2+1)}$$
> Partial fractions: $\frac{s}{(s^2+4)(s^2+1)} = \frac{As+B}{s^2+1} + \frac{Cs+D}{s^2+4}$.
> $s = (As+B)(s^2+4) + (Cs+D)(s^2+1) = (A+C)s^3 + (B+D)s^2 + (4A+C)s + (4B+D)$.
> $A+C=0, 4A+C=1 \implies 3A=1 \implies A=1/3$, $C=-1/3$. $B=D=0$.
> $$X(s) = \frac{1}{3}\frac{s}{s^2+1} - \frac{1}{3}\frac{s}{s^2+4}$$
> Inverse transform: $x(t) = \frac{1}{3}\cos t - \frac{1}{3}\cos 2t$.
>
**7. $x''+x=\cos 3t; x(0)=1, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2 X(s) - s) + X(s) = \frac{s}{s^2+9} \implies (s^2+1)X(s) = s + \frac{s}{s^2+9} = \frac{s^3+10s}{s^2+9}$$
> $$X(s) = \frac{s}{s^2+1} + \frac{s}{(s^2+1)(s^2+9)} \implies \text{Partial fractions on the second term:}$$
> $\frac{s}{(s^2+1)(s^2+9)} = \frac{As+B}{s^2+1} + \frac{Cs+D}{s^2+9} \implies A=1/8, C=-1/8, B=0, D=0$.
> $$X(s) = \frac{s}{s^2+1} + \frac{1}{8}\frac{s}{s^2+1} - \frac{1}{8}\frac{s}{s^2+9} = \frac{9}{8}\frac{s}{s^2+1} - \frac{1}{8}\frac{s}{s^2+9}$$
> Inverse transform: $x(t) = \frac{9}{8}\cos t - \frac{1}{8}\cos 3t$.
>
**8. $x''+9x=1; x(0)=0, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2+9)X(s) = \frac{1}{s} \implies X(s) = \frac{1}{s(s^2+9)} = \frac{A}{s} + \frac{Bs+C}{s^2+9}$$
> $A(s^2+9) + (Bs+C)s = 1 \implies A=1/9, B=-1/9, C=0$.
> $$X(s) = \frac{1/9}{s} - \frac{1}{9}\frac{s}{s^2+9}$$
> Inverse transform: $x(t) = \frac{1}{9} - \frac{1}{9}\cos 3t$.
>
**9. $x''+4x'+3x=1; x(0)=0, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2+4s+3)X(s) = \frac{1}{s} \implies X(s) = \frac{1}{s(s+1)(s+3)} = \frac{A}{s} + \frac{B}{s+1} + \frac{C}{s+3}$$
> $A=1/3$, $B = \frac{1}{(-1)(2)} = -1/2$, $C = \frac{1}{(-3)(-2)} = 1/6$.
> $$X(s) = \frac{1/3}{s} - \frac{1/2}{s+1} + \frac{1/6}{s+3}$$
> Inverse transform: $x(t) = \frac{1}{3} - \frac{1}{2}e^{-t} + \frac{1}{6}e^{-3t}$.
>
**10. $x''+3x'+2x=t; x(0)=0, x'(0)=2$**

> \*\*Solution:\*\*
> $$(s^2 X(s) - 2) + 3(s X(s)) + 2 X(s) = \frac{1}{s^2}$$
> $$(s^2+3s+2)X(s) = 2 + \frac{1}{s^2} = \frac{2s^2+1}{s^2} \implies X(s) = \frac{2s^2+1}{s^2(s+1)(s+2)}$$
> $$X(s) = \frac{A}{s} + \frac{B}{s^2} + \frac{C}{s+1} + \frac{D}{s+2}$$
> $B = \frac{2(0)+1}{(1)(2)} = 1/2$. $C = \frac{2(1)+1}{(1)(1)} = 3$. $D = \frac{2(4)+1}{(4)(-1)} = -9/4$.
> $2s^2+1 = As(s+1)(s+2) + B(s+1)(s+2) + Cs^2(s+2) + Ds^2(s+1)$.
> Look at $s^3$ coefficients: $0 = A + C + D = A + 3 - 9/4 \implies A = -3/4$.
> $$X(s) = -\frac{3/4}{s} + \frac{1/2}{s^2} + \frac{3}{s+1} - \frac{9/4}{s+2}$$
> Inverse transform: $x(t) = -\frac{3}{4} + \frac{1}{2}t + 3e^{-t} - \frac{9}{4}e^{-2t}$.
>
>
## Assignment 5: Translation and Partial Fractions

### Part A: Find the Laplace transforms
**1. $f(t) = t^4 e^{-\pi t}$**

> \*\*Solution:\*\*
> Using first shifting theorem: $\mathcal{L}\{e^{at}t^n\} = \frac{n!}{(s-a)^{n+1}}$.
> $$\mathcal{L}\{t^4 e^{-\pi t}\} = \frac{4!}{(s+\pi)^5} = \frac{24}{(s+\pi)^5}$$
>
**2. $f(t) = t^{3/2} e^{-4t}$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{t^{3/2} e^{-4t}\} = \frac{\Gamma(5/2)}{(s+4)^{5/2}} = \frac{3\sqrt{\pi}}{4(s+4)^{5/2}}$$
>
**3. $f(t) = e^{-2t}\sin(3\pi t)$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{e^{-2t}\sin(3\pi t)\} = \frac{3\pi}{(s+2)^2 + (3\pi)^2} = \frac{3\pi}{(s+2)^2 + 9\pi^2}$$
>
**4. $f(t) = e^{-t/2}\cos(2t-\frac{1}{8}\pi)$**

> \*\*Solution:\*\*
> Using the trigonometric identity $\cos(A-B) = \cos A\cos B + \sin A\sin B$:
> $$\cos(2t-\pi/8) = \cos(2t)\cos(\pi/8) + \sin(2t)\sin(\pi/8)$$
> $$\mathcal{L}\{\cos(2t-\pi/8)\} = \cos(\pi/8)\frac{s}{s^2+4} + \sin(\pi/8)\frac{2}{s^2+4}$$
> Applying the shifting theorem:
> $$\mathcal{L}\{f(t)\} = \frac{\cos(\pi/8)(s+1/2) + 2\sin(\pi/8)}{(s+1/2)^2 + 4}$$
>
### Part B: Find the inverse Laplace transforms (Translation)
**1. $F(s) = \frac{3}{2s-4}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{3/2}{s-2} \implies f(t) = \frac{3}{2}e^{2t}$$
>
**2. $F(s) = \frac{s-1}{(s+1)^3}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{(s+1)-2}{(s+1)^3} = \frac{1}{(s+1)^2} - \frac{2}{(s+1)^3} \implies f(t) = t e^{-t} - t^2 e^{-t}$$
>
**3. $F(s) = \frac{1}{s^2+4s+4}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{1}{(s+2)^2} \implies f(t) = t e^{-2t}$$
>
**4. $F(s) = \frac{s+2}{s^2+4s+5}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{s+2}{(s+2)^2+1} \implies f(t) = e^{-2t}\cos t$$
>
### Part C: Find the inverse Laplace transforms (Partial Fractions)
**1. $F(s) = \frac{1}{s^2-4}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{1}{(s-2)(s+2)} = \frac{1/4}{s-2} - \frac{1/4}{s+2} \implies f(t) = \frac{1}{4}e^{2t} - \frac{1}{4}e^{-2t} = \frac{1}{2}\sinh(2t)$$
>
**2. $F(s) = \frac{5s-6}{s^2-3s}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{5s-6}{s(s-3)} = \frac{2}{s} + \frac{3}{s-3} \implies f(t) = 2 + 3e^{3t}$$
>
**3. $F(s) = \frac{5-2s}{s^2+7s+10}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{5-2s}{(s+2)(s+5)} = \frac{3}{s+2} - \frac{5}{s+5} \implies f(t) = 3e^{-2t} - 5e^{-5t}$$
>
**4. $F(s) = \frac{5s-4}{s^3-s^2-2s}$**

> \*\*Solution:\*\*
> $$F(s) = \frac{5s-4}{s(s-2)(s+1)} = \frac{2}{s} + \frac{1}{s-2} - \frac{3}{s+1} \implies f(t) = 2 + e^{2t} - 3e^{-t}$$
>
## Assignment 6: Advanced Initial-Value Problems

**1. $x''+6x'+25x=0; x(0)=2, x'(0)=3$**

> \*\*Solution:\*\*
> $$(s^2+6s+25)X(s) = 2s + 3 + 12 = 2s + 15$$
> $$X(s) = \frac{2s+15}{(s+3)^2+16} = \frac{2(s+3) + 9}{(s+3)^2+16} = 2\frac{s+3}{(s+3)^2+16} + \frac{9}{4}\frac{4}{(s+3)^2+16}$$
> $$x(t) = 2e^{-3t}\cos(4t) + \frac{9}{4}e^{-3t}\sin(4t)$$
>
**2. $x''-6x'+8x=2; x(0)=0, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2-6s+8)X(s) = \frac{2}{s} \implies X(s) = \frac{2}{s(s-2)(s-4)} = \frac{1/4}{s} - \frac{1/2}{s-2} + \frac{1/4}{s-4}$$
> $$x(t) = \frac{1}{4} - \frac{1}{2}e^{2t} + \frac{1}{4}e^{4t}$$
>
**3. $x''-4x=3t; x(0)=0, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2-4)X(s) = \frac{3}{s^2} \implies X(s) = \frac{3}{s^2(s-2)(s+2)} = -\frac{3/4}{s^2} + \frac{3/16}{s-2} - \frac{3/16}{s+2}$$
> $$x(t) = -\frac{3}{4}t + \frac{3}{16}e^{2t} - \frac{3}{16}e^{-2t} = -\frac{3}{4}t + \frac{3}{8}\sinh(2t)$$
>
**4. $x''+4x'+8x=e^{-t}; x(0)=0, x'(0)=0$**

> \*\*Solution:\*\*
> $$(s^2+4s+8)X(s) = \frac{1}{s+1} \implies X(s) = \frac{1}{(s+1)(s^2+4s+8)} = \frac{1/5}{s+1} - \frac{1}{5}\frac{s+3}{(s+2)^2+4}$$
> $$X(s) = \frac{1}{5}\frac{1}{s+1} - \frac{1}{5}\frac{s+2}{(s+2)^2+4} - \frac{1}{10}\frac{2}{(s+2)^2+4}$$
> $$x(t) = \frac{1}{5}e^{-t} - \frac{1}{5}e^{-2t}\cos(2t) - \frac{1}{10}e^{-2t}\sin(2t)$$
>
**5. $x^{(3)}+x''-6x'=0; x(0)=0, x'(0)=1, x''(0)=1$**

> \*\*Solution:\*\*
> $$s^3 X(s) - s - 1 + s^2 X(s) - 1 - 6s X(s) = 0 \implies (s^3+s^2-6s)X(s) = s+2$$
> $$X(s) = \frac{s+2}{s(s-2)(s+3)} = -\frac{1/3}{s} + \frac{2/5}{s-2} - \frac{1/15}{s+3}$$
> $$x(t) = -\frac{1}{3} + \frac{2}{5}e^{2t} - \frac{1}{15}e^{-3t}$$
>
**6. $x^{(4)}-x=0; x(0)=1, x'(0)=0, x''(0)=0, x^{(3)}(0)=0$**

> \*\*Solution:\*\*
> $$(s^4-1)X(s) = s^3 \implies X(s) = \frac{s^3}{s^4-1} = \frac{1}{2}\frac{s}{s^2-1} + \frac{1}{2}\frac{s}{s^2+1}$$
> $$x(t) = \frac{1}{2}\cosh t + \frac{1}{2}\cos t$$
>
**7. $x^{(4)}+x=0; x(0)=0, x'(0)=0, x''(0)=0, x^{(3)}(0)=1$**

> \*\*Solution:\*\*
> $$(s^4+1)X(s) = 1 \implies X(s) = \frac{1}{s^4+1}$$
> $$x(t) = \frac{1}{\sqrt{2}} \left( \sin\left(\frac{t}{\sqrt{2}}\right)\cosh\left(\frac{t}{\sqrt{2}}\right) - \cos\left(\frac{t}{\sqrt{2}}\right)\sinh\left(\frac{t}{\sqrt{2}}\right) \right)$$
>
**8. $x^{(4)}+13x''+36x=0; x(0)=0, x'(0)=2, x''(0)=0, x^{(3)}(0)=-13$**

> \*\*Solution:\*\*
> $$(s^4+13s^2+36)X(s) = 2s^2 + 13 \implies X(s) = \frac{2s^2+13}{(s^2+4)(s^2+9)} = \frac{1}{s^2+4} + \frac{1}{s^2+9}$$
> $$x(t) = \frac{1}{2}\sin(2t) + \frac{1}{3}\sin(3t)$$
>
**9. $x^{(4)}+8x''+16x=0; x(0)=0, x'(0)=0, x''(0)=0, x^{(3)}(0)=1$**

> \*\*Solution:\*\*
> $$(s^4+8s^2+16)X(s) = 1 \implies X(s) = \frac{1}{(s^2+4)^2}$$
> Using $\mathcal{L}^{-1}\left\{\frac{1}{(s^2+k^2)^2}\right\} = \frac{1}{2k^3}(\sin kt - kt\cos kt)$ with $k=2$:
> $$x(t) = \frac{1}{16}(\sin(2t) - 2t\cos(2t))$$
>
**10. $x^{(4)}+2x''+x=e^{2t}; x(0)=0, x'(0)=0, x''(0)=0, x^{(3)}(0)=0$**

> \*\*Solution:\*\*
> $$(s^2+1)^2 X(s) = \frac{1}{s-2} \implies X(s) = \frac{1}{(s-2)(s^2+1)^2}$$
> $$X(s) = \frac{1/25}{s-2} - \frac{1}{25}\frac{s+2}{s^2+1} + \frac{1}{5}\frac{s-2}{(s^2+1)^2}$$
> $$x(t) = \frac{1}{25}e^{2t} - \frac{1}{25}\cos t - \frac{2}{25}\sin t + \frac{1}{10}t\sin t - \frac{1}{5}(\sin t - t\cos t)$$
>
**11. $x''+4x'+13x=te^{-t}; x(0)=0, x'(0)=2$**

> \*\*Solution:\*\*
> $$X(s) = \frac{2}{(s+2)^2+9} + \frac{1}{(s+1)^2((s+2)^2+9)}$$
>
> Inverse transform:
> $$x(t) = \frac{t e^{- t}}{10} + \frac{\sinh{\left(t \right)}}{50} - \frac{\cosh{\left(t \right)}}{50} + \frac{16 e^{- 2 t} \sin{\left(3 t \right)}}{25} + \frac{e^{- 2 t} \cos{\left(3 t \right)}}{50}$$
>
**12. $x''+6x'+18x=\cos 2t; x(0)=1, x'(0)=-1$**

> \*\*Solution:\*\*
> $$(s^2+6s+18)X(s) - s + 1 - 6 = \frac{s}{s^2+4}$$
> $$X(s) = \frac{s+5}{(s+3)^2+9} + \frac{s}{(s^2+4)((s+3)^2+9)}$$
>
> Inverse transform:
> $$x(t) = \frac{3 \sin{\left(2 t \right)}}{85} + \frac{7 \cos{\left(2 t \right)}}{170} + \frac{307 e^{- 3 t} \sin{\left(3 t \right)}}{510} + \frac{163 e^{- 3 t} \cos{\left(3 t \right)}}{170}$$
>
>
## Assignment 7: Convolution Theorem

### Part A: Find the convolution $f(t)*g(t)$
The convolution is defined as $f(t)*g(t) = \int_{0}^{t} f(\tau)g(t-\tau) d\tau$.

**1. $f(t)=t, g(t)=1$**

> \*\*Solution:\*\*
> $$t * 1 = \int_{0}^{t} \tau \cdot 1 d\tau = \left[ \frac{\tau^2}{2} \right]_0^t = \frac{t^2}{2}$$
>
**2. $f(t)=t, g(t)=e^{at}$**

> \*\*Solution:\*\*
> $$t * e^{at} = \int_{0}^{t} \tau e^{a(t-\tau)} d\tau = e^{at} \int_{0}^{t} \tau e^{-a\tau} d\tau$$
> $$= e^{at} \left[ -\frac{\tau}{a}e^{-a\tau} - \frac{1}{a^2}e^{-a\tau} \right]_0^t = e^{at} \left( -\frac{t}{a}e^{-at} - \frac{1}{a^2}e^{-at} + \frac{1}{a^2} \right) = \frac{e^{at} - at - 1}{a^2}$$
>
**3. $f(t)=g(t)=\sin t$**

> \*\*Solution:\*\*
> Alternatively using Laplace transforms: $\mathcal{L}\{\sin t * \sin t\} = \frac{1}{(s^2+1)^2}$.
> Inverse transform of $\frac{1}{(s^2+1)^2}$ is $\frac{1}{2}(\sin t - t\cos t)$.
> $$\sin t * \sin t = \frac{1}{2}(\sin t - t\cos t)$$
>
**4. $f(t)=t^2, g(t)=\cos t$**

> \*\*Solution:\*\*
> Using Laplace: $\mathcal{L}\{t^2 * \cos t\} = \frac{2}{s^3}\cdot\frac{s}{s^2+1} = \frac{2}{s^2(s^2+1)} = \frac{2}{s^2} - \frac{2}{s^2+1}$.
> $$t^2 * \cos t = \mathcal{L}^{-1}\left\{ \frac{2}{s^2} - \frac{2}{s^2+1} \right\} = 2t - 2\sin t$$
>
**5. $f(t)=g(t)=e^{at}$**

> \*\*Solution:\*\*
> $$e^{at} * e^{at} = \int_{0}^{t} e^{a\tau} e^{a(t-\tau)} d\tau = \int_{0}^{t} e^{at} d\tau = t e^{at}$$
>
**6. $f(t)=e^{at}, g(t)=e^{bt}, (a \ne b)$**

> \*\*Solution:\*\*
> $$e^{at} * e^{bt} = \int_{0}^{t} e^{a\tau} e^{b(t-\tau)} d\tau = e^{bt} \int_{0}^{t} e^{(a-b)\tau} d\tau$$
> $$= e^{bt} \left[ \frac{e^{(a-b)\tau}}{a-b} \right]_0^t = e^{bt} \frac{e^{(a-b)t}-1}{a-b} = \frac{e^{at}-e^{bt}}{a-b}$$
>
### Part B: Find the inverse Laplace transforms using Convolution
**1. $F(s)=\frac{1}{s(s-3)}$**

> \*\*Solution:\*\*
> $$= \mathcal{L}^{-1}\left\{\frac{1}{s}\right\} * \mathcal{L}^{-1}\left\{\frac{1}{s-3}\right\} = 1 * e^{3t} = \int_{0}^{t} e^{3\tau} d\tau = \frac{1}{3}(e^{3t}-1)$$
>
**2. $F(s)=\frac{1}{s(s^2+4)}$**

> \*\*Solution:\*\*
> $$= 1 * \frac{1}{2}\sin 2t = \frac{1}{2}\int_{0}^{t} \sin 2\tau d\tau = \frac{1}{4}(1-\cos 2t)$$
>
**3. $F(s)=\frac{1}{(s^2+9)^2}$**

> \*\*Solution:\*\*
> $$= \frac{1}{3}\sin 3t * \frac{1}{3}\sin 3t = \frac{1}{9} \left( \frac{1}{2\cdot 3}(\sin 3t - 3t\cos 3t) \right) = \frac{1}{54}(\sin 3t - 3t\cos 3t)$$
>
**4. $F(s)=\frac{1}{s^2(s^2+k^2)}$**

> \*\*Solution:\*\*
> $$= t * \frac{1}{k}\sin kt = \frac{1}{k} \int_{0}^{t} (t-\tau)\sin k\tau d\tau = \frac{kt - \sin kt}{k^3}$$
>
**5. $F(s)=\frac{s^2}{(s^2+4)^2}$**

> \*\*Solution:\*\*
> $$= \cos 2t * \cos 2t = \frac{1}{4}(\sin 2t + 2t\cos 2t) \quad \text{(using formula } \frac{s^2-k^2}{(s^2+k^2)^2} = t\cos kt \text{ and linearity)}$$
>
**6. $F(s)=\frac{1}{s(s^2+4s+5)}$**

> \*\*Solution:\*\*
> $$= 1 * e^{-2t}\sin t = \int_{0}^{t} e^{-2\tau}\sin \tau d\tau = \frac{1}{5} - \frac{1}{5}e^{-2t}(\cos t + 2\sin t)$$
>
**7. $F(s)=\frac{s}{(s-3)(s^2+1)}$**

> \*\*Solution:\*\*
> $$= e^{3t} * \cos t = \frac{3 e^{3 t}}{10} + \frac{\sin{\left(t \right)}}{10} - \frac{3 \cos{\left(t \right)}}{10}$$
>
**8. $F(s)=\frac{s}{s^4+5s^2+4} = \frac{s}{(s^2+1)(s^2+4)}$**

> \*\*Solution:\*\*
> $$= \cos t * \frac{1}{2}\sin 2t = \frac{1}{3}(\cos t - \cos 2t) \quad \text{(also matches partial fractions)}$$
>
## Assignment 8: Derivatives and Integrals of Transforms
Formulas: $\mathcal{L}\{t f(t)\} = -\frac{d}{ds}F(s)$ and $\mathcal{L}\left\{\frac{f(t)}{t}\right\} = \int_{s}^{\infty} F(u)du$.

**1. $f(t)=t \sin(3t)$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{t\sin 3t\} = -\frac{d}{ds}\left( \frac{3}{s^2+9} \right) = -3\left(-1(s^2+9)^{-2}(2s)\right) = \frac{6s}{(s^2+9)^2}$$
>
**2. $f(t)=t^2 \cos(2t)$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{t^2\cos 2t\} = \frac{d^2}{ds^2}\left( \frac{s}{s^2+4} \right) = \frac{d}{ds}\left( \frac{4-s^2}{(s^2+4)^2} \right) = \frac{2s^3 - 24s}{(s^2+4)^3}$$
>
**3. $f(t)=te^{2t} \cos(3t)$**

> \*\*Solution:\*\*
> $$\mathcal{L}\{t\cos 3t\} = -\frac{d}{ds}\left( \frac{s}{s^2+9} \right) = \frac{s^2-9}{(s^2+9)^2}$$
> Shift by $s \to s-2$:
> $$\mathcal{L}\{te^{2t}\cos 3t\} = \frac{(s-2)^2-9}{((s-2)^2+9)^2}$$
>
**4. $f(t)=te^{-t} \sin^2 t$**

> \*\*Solution:\*\*
> $$\sin^2 t = \frac{1-\cos 2t}{2} \implies \mathcal{L}\{\sin^2 t\} = \frac{1}{2}\left( \frac{1}{s} - \frac{s}{s^2+4} \right)$$
> Derivative gives $\mathcal{L}\{t\sin^2 t\} = \frac{1}{2}\left( \frac{1}{s^2} - \frac{4-s^2}{(s^2+4)^2} \right)$.
> Shift by $s \to s+1$:
> $$\mathcal{L}\{te^{-t}\sin^2 t\} = \frac{1}{2}\left( \frac{1}{(s+1)^2} + \frac{(s+1)^2-4}{((s+1)^2+4)^2} \right)$$
>
**5. $f(t)=\frac{\sin t}{t}$**

> \*\*Solution:\*\*
> $$\mathcal{L}\left\{\frac{\sin t}{t}\right\} = \int_{s}^{\infty} \frac{1}{u^2+1} du = \left[ \arctan(u) \right]_s^\infty = \frac{\pi}{2} - \arctan(s) = \operatorname{arccot}(s)$$
>
**6. $f(t)=\frac{1-\cos 2t}{t}$**

> \*\*Solution:\*\*
> $$\mathcal{L}\left\{\frac{1-\cos 2t}{t}\right\} = \int_{s}^{\infty} \left( \frac{1}{u} - \frac{u}{u^2+4} \right) du = \left[ \ln(u) - \frac{1}{2}\ln(u^2+4) \right]_s^\infty$$
> $$= \left[ \ln\frac{u}{\sqrt{u^2+4}} \right]_s^\infty = \ln(1) - \ln\frac{s}{\sqrt{s^2+4}} = \frac{1}{2}\ln\left(1 + \frac{4}{s^2}\right)$$
>
**7. $f(t)=\frac{e^{3t}-1}{t}$**

> \*\*Solution:\*\*
> $$\mathcal{L}\left\{\frac{e^{3t}-1}{t}\right\} = \int_{s}^{\infty} \left( \frac{1}{u-3} - \frac{1}{u} \right) du = \left[ \ln\frac{u-3}{u} \right]_s^\infty = 0 - \ln\frac{s-3}{s} = \ln\frac{s}{s-3}$$
>
**8. $f(t)=\frac{e^t-e^{-t}}{t}$**

> \*\*Solution:\*\*
> $$\mathcal{L}\left\{\frac{e^t-e^{-t}}{t}\right\} = \int_{s}^{\infty} \left( \frac{1}{u-1} - \frac{1}{u+1} \right) du = \left[ \ln\frac{u-1}{u+1} \right]_s^\infty = 0 - \ln\frac{s-1}{s+1} = \ln\frac{s+1}{s-1}$$
