# Differential Equations: Chapter 3 Laplace Transform Methods

Assignments 1–8

## Assignment 1: Laplace Transforms by Definition
Apply the definition of the Laplace transform $\mathcal{L}\{f(t)\}=\int_{0}^{\infty}e^{-st}f(t)dt$ to find the Laplace transforms of the following functions $f(t)$.
1. $f(t)=t$
2. $f(t)=t^{2}$
3. $f(t)=e^{3t+1}$
4. $f(t)=\cos t$
5. $f(t)=\sinh t$
6. $f(t)=\sin^{2}t$

## Assignment 2: Standard Laplace Transforms
Use standard Laplace transforms and algebraic identities to find $\mathcal{L}\{f(t)\}$.
1. $f(t)=\sqrt{t}+3t$
2. $f(t)=3t^{5/2}-4t^{3}$
3. $f(t)=t-2e^{3t}$
4. $f(t)=t^{3/2}e^{-10t}$
5. $f(t)=1+\cosh(5t)$
6. $f(t)=\sin(2t)+\cos(2t)$
7. $f(t)=\cos^{2}(2t)$
8. $f(t)=\sin(3t)\cos(3t)$
9. $f(t)=(1+t)^{3}$
10. $f(t)=te^{t}$
11. $f(t)=t \cos(2t)$
12. $f(t)=\sinh^{2}(3t)$

## Assignment 3: Piecewise/Graphical Functions
Apply the definition of the Laplace transform to find the Laplace transforms for the functions represented by the following graphs:
1. A function $f(t)$ defined by a ramp starting at $(0,0)$ and reaching $(1,1)$, then zero for $t > 1$.
2. A pulse function $f(t)$ that is $1$ on the interval $[1, 2]$ and $0$ otherwise.
3. A function $f(t)$ that is a ramp from $(0,0)$ to $(1,1)$ and then stays at $1$ for $t > 1$.

## Assignment 4: Initial-Value Problems
Solve the following initial-value problems using Laplace transforms:
1. $x''+4x=0; x(0)=5, x'(0)=0$
2. $x''+9x=0; x(0)=3, x'(0)=4$
3. $x''-x'-2x=0; x(0)=0, x'(0)=2$
4. $x''+8x'+15x=0; x(0)=2, x'(0)=3$
5. $x''+x=\sin 2t; x(0)=0, x'(0)=0$
6. $x''+4x=\cos t; x(0)=0, x'(0)=0$
7. $x''+x=\cos 3t; x(0)=1, x'(0)=0$
8. $x''+9x=1; x(0)=0, x'(0)=0$
9. $x''+4x'+3x=1; x(0)=0, x'(0)=0$
10. $x''+3x'+2x=t; x(0)=0, x'(0)=2$

## Assignment 5: Translation and Partial Fractions
### Part A
Find the Laplace transforms
1. $f(t)=t^{4}e^{-\pi t}$
2. $f(t)=t^{3/2}e^{-4t}$
3. $f(t)=e^{-2t}\sin(3\pi t)$
4. $f(t)=e^{-t/2}\cos(2t-\frac{1}{8}\pi)$

### Part B
Find the inverse Laplace transforms (Translation)
1. $F(s)=\frac{3}{2s-4}$
2. $F(s)=\frac{s-1}{(s+1)^{3}$
3. $F(s)=\frac{1}{s^{2}+4s+4}$
4. $F(s)=\frac{s+2}{s^{2}+4s+5}$

### Part C
Find the inverse Laplace transforms (Partial Fractions)
1. $F(s)=\frac{1}{s^{2}-4}$
2. $F(s)=\frac{5s-6}{s^{2}-3s}$
3. $F(s)=\frac{5-2s}{s^{2}+7s+10}$
4. $F(s)=\frac{5s-4}{s^{3}-s^{2}-2s}$

## Assignment 6: Advanced Initial-Value Problems
Solve the following using Laplace transforms:
1. $x''+6x'+25x=0; x(0)=2, x'(0)=3$
2. $x''-6x'+8x=2; x(0)=0, x'(0)=0$
3. $x''-4x=3t; x(0)=0, x'(0)=0$
4. $x''+4x'+8x=e^{-t}; x(0)=0, x'(0)=0$
5. $x^{(3)}+x''-6x'=0; x(0)=0, x'(0)=1, x''(0)=1$
6. $x^{(4)}-x=0; x(0)=1, x'(0)=0, x''(0)=0, x^{(3)}(0)=0$
7. $x^{(4)}+x=0; x(0)=0, x'(0)=0, x''(0)=0, x^{(3)}(0)=1$
8. $x^{(4)}+13x''+36x=0; x(0)=0, x'(0)=2, x''(0)=0, x^{(3)}(0)=-13$
9. $x^{(4)}+8x''+16x=0; x(0)=0, x'(0)=0, x''(0)=0, x^{(3)}(0)=1$
10. $x^{(4)}+2x''+x=e^{2t}; x(0)=0, x'(0)=0, x''(0)=0, x^{(3)}(0)=0$
11. $x''+4x'+13x=te^{-t}; x(0)=0, x'(0)=2$
12. $x''+6x'+18x=\cos 2t; x(0)=1, x'(0)=-1$

## Assignment 7: Convolution Theorem
### Part A
Find the convolution $f(t)*g(t)$
1. $f(t)=t, g(t)=1$
2. $f(t)=t, g(t)=e^{at}$
3. $f(t)=g(t)=\sin t$
4. $f(t)=t^2, g(t)=\cos t$
5. $f(t)=g(t)=e^{at}$
6. $f(t)=e^{at}, g(t)=e^{bt}, (a \ne b)$

### Part B
Find the inverse Laplace transforms using Convolution
1. $F(s)=\frac{1}{s(s-3)}$
2. $F(s)=\frac{1}{s(s^{2}+4)}$
3. $F(s)=\frac{1}{(s^{2}+9)^{2}}$
4. $F(s)=\frac{1}{s^{2}(s^{2}+k^{2})}$
5. $F(s)=\frac{s^{2}}{(s^{2}+4)^{2}}$
6. $F(s)=\frac{1}{s(s^{2}+4s+5)}$
7. $F(s)=\frac{s}{(s-3)(s^{2}+1)}$
8. $F(s)=\frac{s}{s^{4}+5s^{2}+4}$

## Assignment 8: Derivatives and Integrals of Transforms
Find the Laplace transform of $f(t)$:
1. $f(t)=t \sin(3t)$
2. $f(t)=t^{2} \cos(2t)$
3. $f(t)=te^{2t} \cos(3t)$
4. $f(t)=te^{-t} \sin^{2}t$
5. $f(t)=\frac{\sin t}{t}$
6. $f(t)=\frac{1-\cos 2t}{t}$
7. $f(t)=\frac{e^{3t}-1}{t}$
8. $f(t)=\frac{e^{t}-e^{-t}}{t}$