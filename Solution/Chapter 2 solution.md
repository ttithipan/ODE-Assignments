# Chapter 2: Higher-Order Linear Differential Equations

## Assignment 1
**For each problem:**
1. **Verify that $y_1$ and $y_2$ are solutions.**
2. **Find a particular solution $y = c_1 y_1 + c_2 y_2$ satisfying the initial conditions.**

**1. $y'' - y = 0; \quad y_1 = e^x, \quad y_2 = e^{-x}; \quad y(0) = 0, \quad y'(0) = 5$**

> **Solution:**
>
> **Verification:**
> $y_1 = e^x \implies y_1'' = e^x$. LHS: $e^x - e^x = 0$. (Verified)
> $y_2 = e^{-x} \implies y_2'' = e^{-x}$. LHS: $e^{-x} - e^{-x} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 e^x + c_2 e^{-x} \implies y' = c_1 e^x - c_2 e^{-x}$.
> $y(0) = c_1 + c_2 = 0 \implies c_2 = -c_1$.
> $y'(0) = c_1 - c_2 = 5 \implies c_1 - (-c_1) = 5 \implies 2c_1 = 5 \implies c_1 = 2.5$.
> $c_2 = -2.5$.
>
> **Answer:** $y = 2.5 e^x - 2.5 e^{-x}$.

**2. $y'' - 9y = 0; \quad y_1 = e^{3x}, \quad y_2 = e^{-3x}; \quad y(0) = -1, \quad y'(0) = 15$**

> **Solution:**
>
> **Verification:**
> $y_1 = e^{3x} \implies y_1'' = 9e^{3x}$. LHS: $9e^{3x} - 9e^{3x} = 0$. (Verified)
> $y_2 = e^{-3x} \implies y_2'' = 9e^{-3x}$. LHS: $9e^{-3x} - 9e^{-3x} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 e^{3x} + c_2 e^{-3x} \implies y' = 3c_1 e^{3x} - 3c_2 e^{-3x}$.
> $y(0) = c_1 + c_2 = -1$.
> $y'(0) = 3c_1 - 3c_2 = 15 \implies c_1 - c_2 = 5$.
> Adding equations: $2c_1 = 4 \implies c_1 = 2$.
> $2 + c_2 = -1 \implies c_2 = -3$.
>
> **Answer:** $y = 2e^{3x} - 3e^{-3x}$.

**3. $y'' + 4y = 0; \quad y_1 = \cos 2x, \quad y_2 = \sin 2x; \quad y(0) = 3, \quad y'(0) = 8$**

> **Solution:**
>
> **Verification:**
> $y_1 = \cos 2x \implies y_1'' = -4\cos 2x$. LHS: $-4\cos 2x + 4\cos 2x = 0$. (Verified)
> $y_2 = \sin 2x \implies y_2'' = -4\sin 2x$. LHS: $-4\sin 2x + 4\sin 2x = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 \cos 2x + c_2 \sin 2x \implies y' = -2c_1 \sin 2x + 2c_2 \cos 2x$.
> $y(0) = c_1(1) + 0 = 3 \implies c_1 = 3$.
> $y'(0) = 0 + 2c_2(1) = 8 \implies 2c_2 = 8 \implies c_2 = 4$.
>
> **Answer:** $y = 3\cos 2x + 4\sin 2x$.

**4. $y'' + 25y = 0; \quad y_1 = \cos 5x, \quad y_2 = \sin 5x; \quad y(0) = 10, \quad y'(0) = -10$**

> **Solution:**
>
> **Verification:**
> $y_1'' = -25\cos 5x$. LHS: $-25\cos 5x + 25\cos 5x = 0$. (Verified)
> $y_2'' = -25\sin 5x$. LHS: $-25\sin 5x + 25\sin 5x = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 \cos 5x + c_2 \sin 5x \implies y' = -5c_1 \sin 5x + 5c_2 \cos 5x$.
> $y(0) = c_1 = 10$.
> $y'(0) = 5c_2 = -10 \implies c_2 = -2$.
>
> **Answer:** $y = 10\cos 5x - 2\sin 5x$.

**5. $y'' - 3y' + 2y = 0; \quad y_1 = e^x, \quad y_2 = e^{2x}; \quad y(0) = 1, \quad y'(0) = 0$**

> **Solution:**
>
> **Verification:**
> $y_1=e^x, y_1'=e^x, y_1''=e^x$. LHS: $e^x - 3e^x + 2e^x = 0$. (Verified)
> $y_2=e^{2x}, y_2'=2e^{2x}, y_2''=4e^{2x}$. LHS: $4e^{2x} - 3(2e^{2x}) + 2e^{2x} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 e^x + c_2 e^{2x} \implies y' = c_1 e^x + 2c_2 e^{2x}$.
> $y(0) = c_1 + c_2 = 1$.
> $y'(0) = c_1 + 2c_2 = 0 \implies c_1 = -2c_2$.
> Substitute: $-2c_2 + c_2 = 1 \implies -c_2 = 1 \implies c_2 = -1$.
> $c_1 = -2(-1) = 2$.
>
> **Answer:** $y = 2e^x - e^{2x}$.

**6. $y'' + y' - 6y = 0; \quad y_1 = e^{2x}, \quad y_2 = e^{-3x}; \quad y(0) = 7, \quad y'(0) = -1$**

> **Solution:**
>
> **Verification:**
> $y_1=e^{2x}, y_1'=2e^{2x}, y_1''=4e^{2x}$. LHS: $4e^{2x} + 2e^{2x} - 6e^{2x} = 0$. (Verified)
> $y_2=e^{-3x}, y_2'=-3e^{-3x}, y_2''=9e^{-3x}$. LHS: $9e^{-3x} - 3e^{-3x} - 6e^{-3x} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 e^{2x} + c_2 e^{-3x} \implies y' = 2c_1 e^{2x} - 3c_2 e^{-3x}$.
> $y(0) = c_1 + c_2 = 7 \implies c_1 = 7 - c_2$.
> $y'(0) = 2c_1 - 3c_2 = -1$.
> $2(7 - c_2) - 3c_2 = -1 \implies 14 - 2c_2 - 3c_2 = -1 \implies 14 - 5c_2 = -1$.
> $15 = 5c_2 \implies c_2 = 3$.
> $c_1 = 7 - 3 = 4$.
>
> **Answer:** $y = 4e^{2x} + 3e^{-3x}$.

**7. $y'' + y' = 0; \quad y_1 = 1, \quad y_2 = e^{-x}; \quad y(0) = -2, \quad y'(0) = 8$**

> **Solution:**
>
> **Verification:**
> $y_1=1, y_1'=0, y_1''=0$. LHS: $0+0=0$. (Verified)
> $y_2=e^{-x}, y_2'=-e^{-x}, y_2''=e^{-x}$. LHS: $e^{-x} - e^{-x} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1(1) + c_2 e^{-x} \implies y' = -c_2 e^{-x}$.
> $y(0) = c_1 + c_2 = -2$.
> $y'(0) = -c_2 = 8 \implies c_2 = -8$.
> $c_1 + (-8) = -2 \implies c_1 = 6$.
>
> **Answer:** $y = 6 - 8e^{-x}$.

**8. $y'' - 3y' = 0; \quad y_1 = 1, \quad y_2 = e^{3x}; \quad y(0) = 4, \quad y'(0) = -2$**

> **Solution:**
>
> **Verification:**
> $y_1=1$. LHS: $0-0=0$. (Verified)
> $y_2=e^{3x}, y_2'=3e^{3x}, y_2''=9e^{3x}$. LHS: $9e^{3x} - 3(3e^{3x}) = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 + c_2 e^{3x} \implies y' = 3c_2 e^{3x}$.
> $y(0) = c_1 + c_2 = 4$.
> $y'(0) = 3c_2 = -2 \implies c_2 = -2/3$.
> $c_1 - 2/3 = 4 \implies c_1 = 12/3 + 2/3 = 14/3$.
>
> **Answer:** $y = \frac{14}{3} - \frac{2}{3}e^{3x}$.

**9. $y'' + 2y' + y = 0; \quad y_1 = e^{-x}, \quad y_2 = xe^{-x}; \quad y(0) = 2, \quad y'(0) = -1$**

> **Solution:**
>
> **Verification:**
> $y_1=e^{-x}$. LHS: $e^{-x} - 2e^{-x} + e^{-x} = 0$. (Verified)
> $y_2=xe^{-x}, y_2'=e^{-x}-xe^{-x}, y_2''=-e^{-x}-(e^{-x}-xe^{-x}) = -2e^{-x}+xe^{-x}$.
> LHS: $(-2e^{-x}+xe^{-x}) + 2(e^{-x}-xe^{-x}) + xe^{-x} = -2e^{-x}+xe^{-x} + 2e^{-x}-2xe^{-x} + xe^{-x} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 e^{-x} + c_2 x e^{-x}$.
> $y' = -c_1 e^{-x} + c_2(e^{-x} - xe^{-x})$.
> $y(0) = c_1 + 0 = 2 \implies c_1 = 2$.
> $y'(0) = -c_1 + c_2 = -1 \implies -2 + c_2 = -1 \implies c_2 = 1$.
>
> **Answer:** $y = 2e^{-x} + xe^{-x}$.

**10. $y'' - 10y' + 25y = 0; \quad y_1 = e^{5x}, \quad y_2 = xe^{5x}; \quad y(0) = 3, \quad y'(0) = 13$**

> **Solution:**
>
> **Verification:**
> $y_1'' = 25e^{5x}$. LHS: $25e^{5x} - 50e^{5x} + 25e^{5x} = 0$. (Verified)
> $y_2'' = 10e^{5x} + 25xe^{5x}$. LHS: $(10e^{5x} + 25xe^{5x}) - 10(e^{5x} + 5xe^{5x}) + 25xe^{5x}$
> $= 10e^{5x} + 25xe^{5x} - 10e^{5x} - 50xe^{5x} + 25xe^{5x} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 e^{5x} + c_2 x e^{5x}$.
> $y' = 5c_1 e^{5x} + c_2(e^{5x} + 5xe^{5x})$.
> $y(0) = c_1 = 3$.
> $y'(0) = 5c_1 + c_2 = 13 \implies 15 + c_2 = 13 \implies c_2 = -2$.
>
> **Answer:** $y = 3e^{5x} - 2xe^{5x}$.

**11. $y'' - 2y' + 2y = 0; \quad y_1 = e^x \cos x, \quad y_2 = e^x \sin x; \quad y(0) = 0, \quad y'(0) = 5$**

> **Solution:**
>
> **Verification:**
> $y_1 = e^x \cos x \implies y_1' = e^x(\cos x - \sin x) \implies y_1'' = e^x(\cos x - \sin x - \sin x - \cos x) = -2e^x \sin x$.
> LHS: $-2e^x \sin x - 2e^x(\cos x - \sin x) + 2e^x \cos x = -2e^x \sin x - 2e^x \cos x + 2e^x \sin x + 2e^x \cos x = 0$. (Verified)
> $y_2$ verified similarly (standard basis for complex roots $1 \pm i$).
>
> **Particular Solution:**
> $y = e^x(c_1 \cos x + c_2 \sin x)$.
> $y' = e^x(c_1 \cos x + c_2 \sin x) + e^x(-c_1 \sin x + c_2 \cos x)$.
> $y(0) = 1(c_1 + 0) = 0 \implies c_1 = 0$.
> $y'(0) = 1(0 + 0) + 1(0 + c_2) = 5 \implies c_2 = 5$.
>
> **Answer:** $y = 5e^x \sin x$.

**12. $y'' + 6y' + 13y = 0; \quad y_1 = e^{-3x} \cos 2x, \quad y_2 = e^{-3x} \sin 2x; \quad y(0) = 2, \quad y'(0) = 0$**

> **Solution:**
>
> **Verification:**
> Standard basis for roots $-3 \pm 2i$. (Verified)
>
> **Particular Solution:**
> $y = e^{-3x}(c_1 \cos 2x + c_2 \sin 2x)$.
> $y' = -3e^{-3x}(c_1 \cos 2x + c_2 \sin 2x) + e^{-3x}(-2c_1 \sin 2x + 2c_2 \cos 2x)$.
> $y(0) = 1(c_1 + 0) = 2 \implies c_1 = 2$.
> $y'(0) = -3(c_1) + 1(2c_2) = 0 \implies -6 + 2c_2 = 0 \implies 2c_2 = 6 \implies c_2 = 3$.
>
> **Answer:** $y = e^{-3x}(2\cos 2x + 3\sin 2x)$.

**13. $x^2 y'' - 2xy' + 2y = 0; \quad y_1 = x, \quad y_2 = x^2; \quad y(1) = 3, \quad y'(1) = 1$**

> **Solution:**
>
> **Verification:**
> $y_1 = x \implies y_1'=1, y_1''=0$. LHS: $0 - 2x(1) + 2x = 0$. (Verified)
> $y_2 = x^2 \implies y_2'=2x, y_2''=2$. LHS: $x^2(2) - 2x(2x) + 2x^2 = 2x^2 - 4x^2 + 2x^2 = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 x + c_2 x^2 \implies y' = c_1 + 2c_2 x$.
> $y(1) = c_1 + c_2 = 3$.
> $y'(1) = c_1 + 2c_2 = 1$.
> Subtracting: $-c_2 = 2 \implies c_2 = -2$.
> $c_1 - 2 = 3 \implies c_1 = 5$.
>
> **Answer:** $y = 5x - 2x^2$.

**14. $x^2 y'' + 2xy' - 6y = 0; \quad y_1 = x^2, \quad y_2 = x^{-3}; \quad y(2) = 10, \quad y'(2) = 15$**

> **Solution:**
>
> **Verification:**
> $y_1 = x^2 \implies y_1'=2x, y_1''=2$. LHS: $x^2(2) + 2x(2x) - 6x^2 = 2x^2 + 4x^2 - 6x^2 = 0$. (Verified)
> $y_2 = x^{-3} \implies y_2'=-3x^{-4}, y_2''=12x^{-5}$. LHS: $x^2(12x^{-5}) + 2x(-3x^{-4}) - 6x^{-3} = 12x^{-3} - 6x^{-3} - 6x^{-3} = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 x^2 + c_2 x^{-3} \implies y' = 2c_1 x - 3c_2 x^{-4}$.
> $y(2) = 4c_1 + c_2/8 = 10 \implies 32c_1 + c_2 = 80$.
> $y'(2) = 4c_1 - 3c_2/16 = 15 \implies 64c_1 - 3c_2 = 240$.
> Multiply first eq by 3: $96c_1 + 3c_2 = 240$.
> Add to second: $160c_1 = 480 \implies c_1 = 3$.
> $32(3) + c_2 = 80 \implies 96 + c_2 = 80 \implies c_2 = -16$.
>
> **Answer:** $y = 3x^2 - 16x^{-3}$.

**15. $x^2 y'' - xy' + y = 0; \quad y_1 = x, \quad y_2 = x \ln x; \quad y(1) = 7, \quad y'(1) = 2$**

> **Solution:**
>
> **Verification:**
> $y_1=x$. LHS: $0 - x(1) + x = 0$. (Verified)
> $y_2=x\ln x, y_2'=\ln x + 1, y_2''=1/x$. LHS: $x^2(1/x) - x(\ln x + 1) + x \ln x = x - x\ln x - x + x\ln x = 0$. (Verified)
>
> **Particular Solution:**
> $y = c_1 x + c_2 x \ln x$.
> $y' = c_1 + c_2(\ln x + 1)$.
> $y(1) = c_1 + 0 = 7 \implies c_1 = 7$.
> $y'(1) = c_1 + c_2(0 + 1) = 7 + c_2 = 2 \implies c_2 = -5$.
>
> **Answer:** $y = 7x - 5x \ln x$.

**16. $x^2 y'' + xy' + y = 0; \quad y_1 = \cos(\ln x), \quad y_2 = \sin(\ln x); \quad y(1) = 2, \quad y'(1) = 3$**

> **Solution:**
>
> **Verification:**
> Cauchy-Euler equation with $m^2 + 1 = 0 \implies m = \pm i$. Basis correct. (Verified)
>
> **Particular Solution:**
> $y = c_1 \cos(\ln x) + c_2 \sin(\ln x)$.
> $y' = -c_1 \sin(\ln x)\frac{1}{x} + c_2 \cos(\ln x)\frac{1}{x}$.
> $y(1) = c_1 \cos(0) + c_2 \sin(0) = c_1 = 2$.
> $y'(1) = -c_1(0)(1) + c_2(1)(1) = c_2 = 3$.
>
> **Answer:** $y = 2\cos(\ln x) + 3\sin(\ln x)$.

## Assignment 2
**1. Let $y_p$ be a particular solution of $y'' + py' + qy = f(x)$ and $y_c$ be a solution of $y'' + py' + qy = 0$. Show that $y = y_c + y_p$ is a solution.**

> **Solution:**
> LHS $= (y_c + y_p)'' + p(y_c + y_p)' + q(y_c + y_p)$
> $= (y_c'' + py_c' + qy_c) + (y_p'' + py_p' + qy_p)$
> $= 0 + f(x) = f(x) = $ RHS. (Verified)

**2. Let $y_p = 1$ and $y_c = c_1 \cos x + c_2 \sin x$. Find solution for $y'' + y = 1$ satisfying $y(0) = -1, y'(0) = 1$.**

> **Solution:**
> $y = c_1 \cos x + c_2 \sin x + 1$.
> $y' = -c_1 \sin x + c_2 \cos x$.
> $y(0) = c_1 + 1 = -1 \implies c_1 = -2$.
> $y'(0) = c_2 = 1$.
>
> **Answer:** $y = -2\cos x + \sin x + 1$.

## Assignment 3
**Determine whether the following pairs of functions are linearly independent or linearly dependent on the real line. You may use the Wronskian function.**

**1. $f(x) = x, \quad g(x) = \cos^2 x + \sin^2 x$**

> **Solution:**
> $g(x) = 1$.
> $W(f,g) = \det \begin{pmatrix} x & 1 \\ 1 & 0 \end{pmatrix} = x(0) - 1(1) = -1$.
> Since $W \neq 0$ everywhere, functions are **linearly independent**.

**2. $f(x) = x^3, \quad g(x) = x^2|x|$**

> **Solution:**
> $g(x) = x^3$ for $x \ge 0$, $-x^3$ for $x < 0$.
> For $x \ge 0$, $g(x) = f(x)$, so $1 \cdot f(x) + (-1) \cdot g(x) = 0$. (Dependent on $[0, \infty)$).
> For $x < 0$, $g(x) = -f(x)$, so $1 \cdot f(x) + 1 \cdot g(x) = 0$. (Dependent on $(-\infty, 0]$).
> On the whole real line: $W(f,g)$ at $x=1$ is 0. At $x=-1$ is 0. Wronskian is identically zero.
> However, there are no constants $c_1, c_2$ (not both 0) such that $c_1 x^3 + c_2 x^2|x| = 0$ for *all* $x$.
> (At $x=1: c_1+c_2=0$. At $x=-1: -c_1+c_2=0 \implies c_1=0, c_2=0$).
> Thus, they are **linearly independent** on $\mathbb{R}$. (Note: Wronskian is zero everywhere, but that doesn't imply dependence if functions are not analytic/solutions to standard ODE).

**3. $f(x) = 1+x, \quad g(x) = 1+|x|$**

> **Solution:**
> **Linearly independent** on $\mathbb{R}$ (Cannot express one as scalar multiple of other across zero).

**4. $f(x) = xe^x, \quad g(x) = |x|e^x$**

> **Solution:**
> **Linearly independent** on $\mathbb{R}$.

**5. $f(x) = \sin^2 x, \quad g(x) = 1 - \cos 2x$**

> **Solution:**
> $1 - \cos 2x = 2 \sin^2 x$.
> $g(x) = 2 f(x)$.
> **Linearly dependent**.

**6. $f(x) = e^x \sin x, \quad g(x) = e^x \cos x$**

> **Solution:**
> $W = \det \begin{pmatrix} e^x \sin x & e^x \cos x \\ e^x(\sin x + \cos x) & e^x(\cos x - \sin x) \end{pmatrix}$
> $= e^{2x}(\sin x \cos x - \sin^2 x) - e^{2x}(\sin x \cos x + \cos^2 x)$
> $= e^{2x}(-\sin^2 x - \cos^2 x) = -e^{2x} \neq 0$.
> **Linearly independent**.

**7. $f(x) = 2\cos x + 3\sin x, \quad g(x) = 3\cos x - 2\sin x$**

> **Solution:**
> Ratio is not constant (e.g., at $x=0$, $f=2, g=3$; at $x=\pi/2$, $f=3, g=-2$).
> **Linearly independent**.

## Assignment 4
**1. Show that $y_1 = x^2$ and $y_2 = x^3$ are two different solutions of $x^2 y'' - 4xy' + 6y = 0$, both satisfying the initial conditions $y(0) = 0 = y'(0)$. Explain why these facts do not contradict Theorem 2 (uniqueness).**

> **Solution:**
> $y_1 = x^2 \implies y_1'=2x, y_1''=2$. LHS: $x^2(2) - 4x(2x) + 6(x^2) = 2x^2 - 8x^2 + 6x^2 = 0$. (Solution).
> $y_1(0)=0, y_1'(0)=0$. (Satisfies IC).
> $y_2 = x^3 \implies y_2'=3x^2, y_2''=6x$. LHS: $x^2(6x) - 4x(3x^2) + 6(x^3) = 6x^3 - 12x^3 + 6x^3 = 0$. (Solution).
> $y_2(0)=0, y_2'(0)=0$. (Satisfies IC).
>
> **Explanation:** Theorem 2 (Existence and Uniqueness) requires the differential equation to be in the form $y'' + p(x)y' + q(x)y = 0$ with continuous $p(x), q(x)$ on an interval containing the initial point $x_0$.
> Rewriting standard form: $y'' - \frac{4}{x}y' + \frac{6}{x^2}y = 0$.
> Functions $p(x)=-4/x$ and $q(x)=6/x^2$ are discontinuous at $x_0=0$. Thus, the uniqueness theorem does not apply at $x=0$.

**2. (a) Show that $y_1 = x^3$ and $y_2 = |x^3|$ are linearly independent solutions on the real line of the equation $x^2 y'' - 3xy' + 3y = 0$.**

> **Solution:**
> Verified solutions by substitution (piecewise for $y_2$).
> Independence showed in Assignment 3 Q2 concept.

**(b) Verify that the Wronskian $W(y_1, y_2)$ is identically zero. Explain why these facts do not contradict Theorem 3.**

> **Solution:**
> Wronskian is 0 everywhere (calculated previously).
> Theorem 3 states that if $W(y_1, y_2) = 0$ at *some* point in interval $I$, then $y_1, y_2$ are linearly dependent on $I$, *provided that* they are solutions to $y'' + p(x)y' + q(x)y = 0$ with continuous coefficients on $I$.
> Here, coefficients $-3/x$ and $3/x^2$ are discontinuous at $x=0$. The interval containing all real numbers includes the singular point $x=0$, so the theorem's assumptions are not met for the entire real line.

**3. Show that $y_1 = \sin(x^2)$ and $y_2 = \cos(x^2)$ are linearly independent functions, but their Wronskian vanishes at $x=0$. Why does this imply that there is no differential equation of the form $y'' + p(x)y' + q(x)y = 0$, with both $p$ and $q$ continuous everywhere, having both $y_1$ and $y_2$ as solutions?**

> **Solution:**
> $W(y_1, y_2) = \det \begin{pmatrix} \sin(x^2) & \cos(x^2) \\ 2x\cos(x^2) & -2x\sin(x^2) \end{pmatrix} = -2x\sin^2(x^2) - 2x\cos^2(x^2) = -2x$.
> $W(0) = 0$. Since $W$ is not identically zero (e.g. $W(1)=-2$), functions are independent.
> **Implication:** Abel's Identity states $W(x) = C e^{-\int p(x) dx}$. If $p(x)$ is continuous everywhere, $W(x)$ can never be zero unless it is identically zero everywhere. Here $W(0)=0$ but $W(x) \neq 0$ elsewhere, which is impossible for continuous coefficients. Thus no such ODE exists.

## Assignment 5
**Apply Theorems 5 and 6 to find general solutions.**

**1. $y'' - 3y' + 2y = 0$**

> **Answer:** $r=1, 2 \implies y = c_1 e^x + c_2 e^{2x}$.

**2. $y'' + 2y' - 15y = 0$**

> **Answer:** $r=-5, 3 \implies y = c_1 e^{-5x} + c_2 e^{3x}$.

**3. $y'' + 5y' = 0$**

> **Answer:** $r=0, -5 \implies y = c_1 + c_2 e^{-5x}$.

**4. $2y'' + 3y' = 0$**

> **Answer:** $r=0, -3/2 \implies y = c_1 + c_2 e^{-3x/2}$.

**5. $2y'' - y' - y = 0$**

> **Answer:** $r=-1/2, 1 \implies y = c_1 e^{-x/2} + c_2 e^x$.

**6. $4y'' + 8y' + 3y = 0$**

> **Answer:** $r=-1/2, -3/2 \implies y = c_1 e^{-x/2} + c_2 e^{-3x/2}$.

**7. $4y'' + 4y' + y = 0$**

> **Answer:** $r=-1/2$ (mult 2) $\implies y = c_1 e^{-x/2} + c_2 x e^{-x/2}$.

**8. $9y'' - 12y' + 4y = 0$**

> **Answer:** $r=2/3$ (mult 2) $\implies y = c_1 e^{2x/3} + c_2 x e^{2x/3}$.

**9. $6y'' - 7y' - 20y = 0$**

> **Answer:** $r=5/2, -4/3 \implies y = c_1 e^{5x/2} + c_2 e^{-4x/3}$.

**10. $35y'' - y' - 12y = 0$**

> **Answer:** $r=3/5, -4/7 \implies y = c_1 e^{3x/5} + c_2 e^{-4x/7}$.

## Assignment 6
**Match general solutions with ODEs.**

**1. $y(x) = c_1 + c_2 e^{10x}$**

> **Equation:** $y'' - 10y' = 0$.

**2. $y(x) = c_1 e^{10x} + c_2 e^{-10x}$**

> **Equation:** $y'' - 100y = 0$.

**3. $y(x) = c_1 e^{10x} + c_2 x e^{10x}$**

> **Equation:** $y'' - 20y' + 100y = 0$.

**4. $y(x) = c_1 e^{10x} + c_2 e^{100x}$**

> **Equation:** $y'' - 110y' + 1000y = 0$.

**5. $y(x) = c_1 + c_2 x$**

> **Equation:** $y'' = 0$.

**6. $y(x) = e^x(c_1 e^{\sqrt{2}x} + c_2 e^{-\sqrt{2}x}) = c_1 e^{(1+\sqrt{2})x} + c_2 e^{(1-\sqrt{2})x}$**

> **Equation:** $y'' - 2y' - y = 0$.

## Assignment 7
**Show linear dependence/find linear combination.**

**1. $f(x)=2x, g(x)=3x^2, h(x)=5x-8x^2$**

> **Solution:** $2.5f(x) - \frac{8}{3}g(x) - h(x) = 0$. **Dependent**.

**2. $f(x)=5, g(x)=2-3x^2, h(x)=10+15x^2$**

> **Solution:** $4f(x) - 5g(x) - h(x) = 0$. **Dependent**.

**3. $f(x)=0, g(x)=\sin x, h(x)=e^x$**

> **Solution:** $1\cdot f(x) + 0\cdot g(x) + 0\cdot h(x) = 0$. **Dependent**.

**4. $f(x)=17, g(x)=2\sin^2 x, h(x)=3\cos^2 x$**

> **Solution:** $f(x) = 17 = 8.5(2\sin^2 x + 2\cos^2 x) = 8.5(g(x) + \frac{2}{3}h(x))$. **Dependent**.

**5. $f(x)=17, g(x)=\cos^2 x, h(x)=\cos 2x$**

> **Solution:** $f(x) = 17(1) = 17(2g(x) - h(x))$. **Dependent**.

**6. $f(x)=e^x, g(x)=\cosh x, h(x)=\sinh x$**

> **Solution:** $f(x) = g(x) + h(x)$. **Dependent**.

## Assignment 8
**Prove linear independence using Wronskian.**

**1. $f=1, g=x, h=x^2$**

> **Solution:** $W=2 \neq 0$. **Independent**.

**2. $f=e^x, g=e^{2x}, h=e^{3x}$**

> **Solution:** $W = 2e^{6x} \neq 0$. **Independent**.

**3. $f=e^x, g=\cos x, h=\sin x$**

> **Solution:** $W = 2e^x \neq 0$. **Independent**.

**4. $f(x)=e^x, g(x)=x^{-2}, h(x)=x^{-2}\ln x$; Interval: $x>0$**

> **Solution:** $W = \frac{(x^2+5x+4)e^x}{x^7} \neq 0$ for $x>0$. **Independent**.

**5. $f(x)=x, g(x)=xe^x, h(x)=x^2e^x$; Interval: $\mathbb{R}$**

> **Solution:** $W = x^3 e^{2x}$. Non-zero almost everywhere. **Independent**.

**6. $f(x)=x, g(x)=\cos(\ln x), h(x)=\sin(\ln x)$; Interval: $x>0$**

> **Solution:** $W = \frac{2}{x^2} \neq 0$. **Independent**.

## Assignment 9
**Find a particular solution satisfying initial conditions.**

**1. $y^{(3)} + 2y'' - y' - 2y = 0; \quad y(0)=1, y'(0)=2, y''(0)=0$**

> **Solution:** $y = \frac{4}{3}e^x - \frac{1}{3}e^{-2x}$.

**2. $y^{(3)} - 6y'' + 11y' - 6y = 0; \quad y(0)=0, y'(0)=0, y''(0)=3$**

> **Solution:** $y = 1.5e^x - 3e^{2x} + 1.5e^{3x}$.

**3. $y^{(3)} - 3y'' + 3y' - y = 0; \quad y(0)=2, y'(0)=0, y''(0)=0$**

> **Solution:** $y = e^x(2 - 2x + x^2)$.

**4. $y^{(3)} - 5y'' + 8y' - 4y = 0; \quad y(0)=1, y'(0)=4, y''(0)=0$**

> **Solution:** $y = -12e^x + 13e^{2x} - 10x e^{2x}$.

**5. $y^{(3)} + 9y' = 0; \quad y(0)=3, y'(0)=-1, y''(0)=2$**

> **Solution:** $y = \frac{29}{9} - \frac{2}{9}\cos 3x - \frac{1}{3}\sin 3x$.

**6. $y^{(3)} - 3y'' + 4y' - 2y = 0; \quad y(0)=1, y'(0)=0, y''(0)=0$**

> **Solution:** $y = 2e^x - e^x \cos x - e^x \sin x$.

## Assignment 10
**Find $y_p(x)$.**

**1. $y'' + y = 3x; \quad y(0)=2, y'(0)=-2$**

> **Answer:** $y = 2\cos x - 5\sin x + 3x$.

**2. $y'' - 4y = 12; \quad y(0)=0, y'(0)=10$**

> **Answer:** $y = 4e^{2x} - e^{-2x} - 3$.

**3. $y'' - 2y' - 3y = 6; \quad y(0)=3, y'(0)=11$**

> **Answer:** $y = e^{-x} + 4e^{3x} - 2$.

**4. $y'' - 2y' + 2y = 2x; \quad y(0)=4, y'(0)=8$**

> **Answer:** $y = e^x(3\cos x + 4\sin x) + x + 1$.

## Assignment 11
**Find general solutions.**

**1. $y'' - 4y = 0$**

> **Answer:** $y = c_1 e^{2x} + c_2 e^{-2x}$.

**2. $2y'' - 3y' = 0$**

> **Answer:** $y = c_1 + c_2 e^{3x/2}$.

**3. $y'' + 3y' - 10y = 0$**

> **Answer:** $y = c_1 e^{-5x} + c_2 e^{2x}$.

**4. $2y'' - 7y' + 3y = 0$**

> **Answer:** $y = c_1 e^{x/2} + c_2 e^{3x}$.

**5. $y'' + 6y' + 9y = 0$**

> **Answer:** $y = c_1 e^{-3x} + c_2 x e^{-3x}$.

**6. $y'' + 5y' + 5y = 0$**

> **Answer:** $y = c_1 e^{\frac{-5+\sqrt{5}}{2}x} + c_2 e^{\frac{-5-\sqrt{5}}{2}x}$.

**7. $4y'' - 12y' + 9y = 0$**

> **Answer:** $y = c_1 e^{3x/2} + c_2 x e^{3x/2}$.

**8. $y'' - 6y' + 13y = 0$**

> **Answer:** $y = e^{3x}(c_1 \cos 2x + c_2 \sin 2x)$.

**9. $y'' + 8y' + 25y = 0$**

> **Answer:** $y = e^{-4x}(c_1 \cos 3x + c_2 \sin 3x)$.

**10. $5y^{(4)} + 3y^{(3)} = 0$**

> **Answer:** $y = c_1 + c_2 x + c_3 x^2 + c_4 e^{-3x/5}$.

**11. $y^{(4)} - 8y^{(3)} + 16y'' = 0$**

> **Answer:** $y = c_1 + c_2 x + c_3 e^{4x} + c_4 x e^{4x}$.

**12. $y^{(4)} - 3y^{(3)} + 3y'' - y' = 0$**

> **Answer:** $y = c_1 + e^x(c_2 + c_3 x + c_4 x^2)$.

**13. $9y^{(3)} + 12y'' + 4y' = 0$**

> **Answer:** $y = c_1 + c_2 e^{-2x/3} + c_3 x e^{-2x/3}$.

**14. $y^{(4)} + 3y'' - 4y = 0$**

> **Answer:** $y = c_1 e^x + c_2 e^{-x} + c_3 \cos 2x + c_4 \sin 2x$.

**15. $y^{(4)} - 8y'' + 16y = 0$**

> **Answer:** $y = c_1 e^{2x} + c_2 x e^{2x} + c_3 e^{-2x} + c_4 x e^{-2x}$.

**16. $y^{(4)} + 18y'' + 81y = 0$**

> **Answer:** $y = (c_1 + c_2 x)\cos 3x + (c_3 + c_4 x)\sin 3x$.

**17. $6y^{(4)} + 11y'' + 4y = 0$**

> **Answer:** $y = c_1 \cos(x/\sqrt{2}) + c_2 \sin(x/\sqrt{2}) + c_3 \cos(2x/\sqrt{3}) + c_4 \sin(2x/\sqrt{3})$.

**18. $y^{(4)} = 16y$**

> **Answer:** $y = c_1 e^{2x} + c_2 e^{-2x} + c_3 \cos 2x + c_4 \sin 2x$.

**19. $y^{(3)} + y'' - y' - y = 0$**

> **Answer:** $y = c_1 e^x + c_2 e^{-x} + c_3 x e^{-x}$.

**20. $y^{(4)} + 2y^{(3)} + 3y'' + 2y' + y = 0$**

> **Answer:** $y = e^{-x/2}[(c_1 + c_2 x)\cos(\frac{\sqrt{3}}{2}x) + (c_3 + c_4 x)\sin(\frac{\sqrt{3}}{2}x)]$.

## Assignment 12
**Solve initial value problems.**

**1. $y'' - 4y' + 3y = 0; \quad y(0)=7, y'(0)=11$**

> **Answer:** $y = 5e^x + 2e^{3x}$.

**2. $9y'' + 6y' + 4y = 0; \quad y(0)=3, y'(0)=4$**

> **Answer:** $y = e^{-x/3}(3\cos \frac{x}{\sqrt{3}} + 5\sqrt{3}\sin \frac{x}{\sqrt{3}})$.

**3. $y'' - 6y' + 25y = 0; \quad y(0)=3, y'(0)=1$**

> **Answer:** $y = e^{3x}(3\cos 4x - 2\sin 4x)$.

**4. $2y^{(3)} - 3y'' - 2y' = 0; \quad y(0)=1, y'(0)=-1, y''(0)=3$**

> **Answer:** $y = -7/2 + 4e^{-x/2} + \frac{1}{2}e^{2x}$.

**5. $3y^{(3)} + 2y'' = 0; \quad y(0)=-1, y'(0)=0, y''(0)=1$**

> **Answer:** $y = -\frac{13}{4} + \frac{3}{2}x + \frac{9}{4}e^{-2x/3}$.

**6. $y^{(3)} + 10y'' + 25y' = 0; \quad y(0)=3, y'(0)=4, y''(0)=5$**

> **Answer:** $y = 4.8 - 1.8e^{-5x} - 5x e^{-5x}$.

## Assignment 13
**First find a small integral root by inspection.**

**1. $y^{(3)} + 3y'' - 4y = 0$**

> **Answer:** $y = c_1 e^x + c_2 e^{-2x} + c_3 x e^{-2x}$.

**2. $y^{(3)} - y'' - 4y' - 2y = 0$**

> **Answer:** $y = c_1 e^{-x} + c_2 e^{(1+\sqrt{3})x} + c_3 e^{(1-\sqrt{3})x}$.

**3. $y^{(3)} + 27y = 0$**

> **Answer:** $y = c_1 e^{-3x} + e^{1.5x}(c_2 \cos \frac{3\sqrt{3}}{2}x + c_3 \sin \frac{3\sqrt{3}}{2}x)$.

**4. $y^{(4)} - y^{(3)} + y'' - 3y' - 6y = 0$**

> **Answer:** $y = c_1 e^{-x} + c_2 e^{2x} + c_3 \cos \sqrt{3}x + c_4 \sin \sqrt{3}x$.

**5. $y^{(3)} + 3y'' + 4y' - 8y = 0$**

> **Answer:** $y = c_1 e^x + e^{-2x}(c_2 \cos 2x + c_3 \sin 2x)$.

**6. $y^{(4)} + y^{(3)} - 3y'' - 5y' - 2y = 0$**

> **Answer:** $y = e^{-x}(c_1 + c_2 x + c_3 x^2) + c_4 e^{2x}$.

**Find general solution.**

**1. $y^{(3)} + 3y'' - 54y = 0$ with $y=e^{3x}$**

> **Answer:** $y = c_1 e^{3x} + e^{-3x}(c_2 \cos 3x + c_3 \sin 3x)$.

**2. $3y^{(3)} - 2y'' + 12y' - 8y = 0$ with $y=e^{2x/3}$**

> **Answer:** $y = c_1 e^{2x/3} + c_2 \cos 2x + c_3 \sin 2x$.

**3. $6y^{(4)} + 5y^{(3)} + 25y'' + 20y' + 4y = 0$ with $y=\cos 2x$**

> **Answer:** $y = c_1 \cos 2x + c_2 \sin 2x + c_3 e^{-x/2} + c_4 e^{-x/3}$.

**4. $9y^{(3)} + 11y'' + 4y' - 14y = 0$ with $y=e^{-x}\sin x$**

> **Answer:** $y = e^{-x}(c_1 \cos x + c_2 \sin x) + c_3 e^{7x/9}$.

**5. Find $y(x)$ s.t. $y^{(4)} = y$, $y^{(3)} = y'$...**

> **Answer:** $y = 12.5 e^x + 3e^{-x} + 2.5 \cos x + 2.5 \sin x$.

**6. $y'' - 2iy' + 3y = 0$**

> **Answer:** $y = c_1 e^{3ix} + c_2 e^{-ix}$.

## Assignment 14
**Find particular solution $y_p$.**

**1. $y'' + 16y = e^{3x}$**

> **Answer:** $y_p = \frac{1}{25}e^{3x}$.

**2. $y'' - y' - 2y = 3x + 4$**

> **Answer:** $y_p = -1.5x - 1.25$.

**3. $y'' - y' - 6y = 2\sin 3x$**

> **Answer:** $y_p = \frac{1}{39}(\cos 3x - 5\sin 3x)$.

**4. $4y'' + 4y' + y = 3xe^x$**

> **Answer:** $y_p = (\frac{1}{3}x - \frac{4}{9})e^x$.

**5. $y'' + y' + y = \sin^2 x$**

> **Answer:** $y_p = 0.5 + \frac{3}{26}\cos 2x - \frac{1}{13}\sin 2x$.

**6. $2y'' + 4y' + 7y = x^2$**

> **Answer:** $y_p = \frac{1}{7}x^2 - \frac{8}{49}x + \frac{4}{343}$.

**7. $y'' - 4y = \sinh x$**

> **Answer:** $y_p = -\frac{1}{3}\sinh x$.

**8. $y'' - 4y = \cosh 2x$**

> **Answer:** $y_p = \frac{x}{4}\sinh 2x$.

**9. $y'' + 2y' - 3y = 1 + xe^x$**

> **Answer:** $y_p = -1/3 + e^x(\frac{1}{8}x^2 - \frac{1}{16}x)$.

**10. $y'' + 9y = 2\cos 3x + 3\sin 3x$**

> **Answer:** $y_p = x(-\frac{1}{2}\cos 3x + \frac{1}{3}\sin 3x)$.

**11. $y^{(3)} + 4y' = 3x - 1$**

> **Answer:** $y_p = \frac{3}{8}x^2 - \frac{1}{4}x$.

**12. $y^{(3)} + y' = 2\sin x$**

> **Answer:** $y_p = -x \sin x$.

**13. $y'' + 2y' + 5y = e^x \sin x$**

> **Answer:** $y_p = \frac{1}{65}e^x(-4\cos x + 7\sin x)$.

**14. $y^{(4)} - 2y'' + y = xe^x$**

> **Answer:** $y_p = \frac{1}{24}x^3 e^x$.

**15. $y^{(5)} + 5y^{(4)} - y = 17$**

> **Answer:** $y_p = -17$.

**16. $y'' + 9y = 2x^2 e^{3x} + 5$**

> **Answer:** $y_p = \frac{5}{9} + e^{3x}(\frac{1}{9}x^2 - \frac{2}{27}x + \frac{1}{81})$.

**17. $y'' + y = \sin x + x \cos x$**

> **Answer:** $y_p = \frac{1}{4}x^2\sin x - \frac{1}{4}x\cos x$.

**18. $y^{(4)} - 5y'' + 4y = e^x - xe^{2x}$**

> **Answer:** $y_p = -\frac{1}{6}xe^x - e^{2x}(\frac{1}{24}x^2 + \frac{1}{12}x - \frac{1}{18})$.
> *(Note: Calculated form only $Ax e^x + (Bx^2+Cx)e^{2x}$ asked, but specific solution provided for completeness).*

**19. $y^{(5)} + 2y^{(3)} + 2y'' = 3x^2 - 1$**

> **Answer:** $y_p = \frac{1}{8}x^4 - \frac{1}{2}x^2$.

**20. $y^{(3)} - y = e^x + 7$**

> **Answer:** $y_p = \frac{1}{3}xe^x - 7$.

## Assignment 15
**Set up the form of $y_p$.**

**1. $y'' - 2y' + 2y = e^x \sin x$**

> **Form:** $y_p = x e^x (A\cos x + B \sin x)$.

**2. $y^{(5)} - y^{(3)} = e^x + 2x^2 - 5$**

> **Form:** $y_p = Ax e^x + x^3(Bx^2 + Cx + D)$.

**3. $y'' + 4y = 3x \cos 2x$**

> **Form:** $y_p = x(Ax+B)\cos 2x + x(Cx+D)\sin 2x$.

**4. $y^{(3)} + y'' - 12y' = x - 2x e^{-3x}$**

> **Form:** $y_p = x(Ax+B) + e^{-3x}(Cx+D)$.

**5. $y'' + 3y' + 2y = x(e^x - e^{-2x})$**

> **Form:** $y_p = (Ax+B)e^x + x(Cx+D)e^{-2x}$.

**6. $y'' - 6y' + 13y = x e^{3x} \sin 2x$**

> **Form:** $y_p = x e^{3x} [(Ax+B)\cos 2x + (Cx+D)\sin 2x]$.

**7. $y^{(4)} + 5y'' + 4y = \sin x + \cos 2x$**

> **Form:** $y_p = x(A\cos x + B\sin x) + x(C\cos 2x + D\sin 2x)$.

**8. $y^{(4)} + 9y'' = (x^2+1)\sin 3x$**

> **Form:** $y_p = x(Ax^2+Bx+C)\cos 3x + x(Dx^2+Ex+F)\sin 3x$.

**9. $(D-1/3)(D^2-4)y = x e^x + e^{2x} + e^{-2x}$**

> **Form:** $y_p = (Ax+B)e^x + Cx e^{2x} + Dx e^{-2x}$.

**10. $y^{(4)} - 2y'' + y = x^2 \cos x$**

> **Form:** $y_p = (Ax^2+Bx+C)\cos x + (Dx^2+Ex+F)\sin x$.

## Assignment 16
**Solve initial value problems for a particular solution.**

**1. $y'' + 4y = 2x; \quad y(0)=1, y'(0)=2$**

> **Solution:** $y_p = x/2$.
> $y = \cos 2x + 0.75 \sin 2x + 0.5x$.

**2. $y'' + 3y' + 2y = e^x; \quad y(0)=0, y'(0)=3$**

> **Solution:** $y_p = e^x/6$.
> $y = 0.5 e^{-x} - \frac{2}{3} e^{-2x} + \frac{1}{6} e^x$.

**3. $y'' + 9y = \sin 2x; \quad y(0)=1, y'(0)=0$**

> **Solution:** $y_p = \frac{1}{5}\sin 2x$.
> $y = \cos 3x - \frac{2}{15}\sin 3x + \frac{1}{5}\sin 2x$.

**4. $y'' + y = \cos x; \quad y(0)=1, y'(0)=-1$**

> **Solution:** $y_p = \frac{1}{2}x\sin x$.
> $y = \cos x - \sin x + \frac{1}{2}x\sin x$.

**5. $y'' - 2y' + 2y = x+1; \quad y(0)=3, y'(0)=0$**

> **Solution:** $y_p = 0.5x + 1$.
> $y = e^x(2\cos x - 2.5\sin x) + 0.5x + 1$.

**6. $y^{(4)} - 4y'' = x^2; \quad y(0)=y'(0)=y''(0)=y'''(0)=-1$**

> **Solution:** $y_p = -\frac{1}{48}x^4 - \frac{1}{16}x^2$.
> Full answer: $y(x) = -\frac{1}{48}x^4 - \frac{1}{16}x^2 - \frac{3}{4}x - \frac{25}{32} - \frac{11}{64}e^{2x} - \frac{3}{64}e^{-2x}$.

**7. $y^{(3)} - 2y'' + y' = 1 + xe^x; \quad y(0)=y'(0)=0, y''(0)=1$**

> **Solution:** $y_p = x + e^x(\frac{1}{6}x^3 - x^2)$.
> Full answer: $y(x) = x + 4 + e^x(\frac{1}{6}x^3 - \frac{1}{2}x^2 + 3x - 4)$.

**8. $y'' + 2y' + 2y = \sin 3x; \quad y(0)=2, y'(0)=0$**

> **Solution:** $y_p = -\frac{7}{85}\sin 3x - \frac{6}{85}\cos 3x$.
> Full answer: $y(x) = -\frac{7}{85}\sin 3x - \frac{6}{85}\cos 3x + e^{-x}(\frac{197}{85}\sin x + \frac{176}{85}\cos x)$.

**9. $y^{(3)} + y'' = x + e^x; \quad y(0)=1, y'(0)=0, y''(0)=1$**

> **Solution:** $y_p = \frac{1}{6}x^3 - \frac{1}{2}x^2 + \frac{1}{2}e^x$.
> Full answer: $y(x) = \frac{1}{6}x^3 - \frac{1}{2}x^2 + x - 1 + \frac{1}{2}e^x + \frac{3}{2}e^{-x}$.

**10. $y^{(4)} - y = 5; \quad y(0)=y'(0)=y''(0)=y'''(0)=0$**

> **Solution:** $y_p = -5$.
> $y = -2.5(\cos x + \cosh x) + 5$.

## Assignment 17
**Variation of Parameters.**

**1. $y'' + 3y' + 2y = 4e^x$**

> **Answer:** $y_p = \frac{2}{3}e^x$.

**2. $y'' - 2y' - 8y = 3e^{-2x}$**

> **Answer:** $y_p = -\frac{1}{2}x e^{-2x}$.

**3. $y'' - 4y' + 4y = 2e^{2x}$**

> **Answer:** $y_p = x^2 e^{2x}$.

**4. $y'' - 4y = \sinh 2x$**

> **Answer:** $y_p = \frac{x}{4}\sinh 2x$.

**5. $y'' + 4y = \cos 3x$**

> **Answer:** $y_p = -\frac{1}{5}\cos 3x$.

**6. $y'' + 9y = \sin 3x$**

> **Answer:** $y_p = -\frac{1}{6}x \cos 3x$.

**7. $y'' + 9y = 2\sec 3x$**

> **Answer:** $y_p = \frac{2}{9}\cos 3x \ln|\cos 3x| + \frac{2}{3}x \sin 3x$.

**8. $y'' + y = \csc^2 x$**

> **Answer:** $y_p = \cos x \ln|\csc x + \cot x| - 1$.

**9. $y'' + 4y = \sin^2 x$**

> **Answer:** $y_p = \frac{1}{8} - \frac{1}{8}\cos 2x$.

**10. $y'' - 4y = xe^x$**

> **Answer:** $y_p = -\frac{1}{3}x e^x - \frac{2}{9}e^x$.
