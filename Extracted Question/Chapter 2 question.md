# Differential Equations: Higher-Order Linear Equations (Assignments 1-17)

## Assignment 1: Introduction to Second-Order Linear Equations
Instruction: First verify that $y_{1}$ and $y_{2}$ are solutions of the differential equation. Then find a particular solution of the form $y=c_{1}y_{1}+c_{2}y_{2}$ that satisfies the given initial conditions.
1. $y^{\prime\prime}-y=0$; $y_{1}=e^{x}$, $y_{2}=e^{-x}$; $y(0)=0$, $y^{\prime}(0)=5$
2. $y^{\prime\prime}-9y=0$; $y_{1}=e^{3x}$, $y_{2}=e^{-3x}$; $y(0)=-1$, $y^{\prime}(0)=15$
3. $y^{\prime\prime}+4y=0$; $y_{1}=\cos 2x$, $y_{2}=\sin 2x$; $y(0)=3$, $y^{\prime}(0)=8$
4. $y^{\prime\prime}+25y=0$; $y_{1}=\cos 5x$, $y_{2}=\sin 5x$; $y(0)=10$, $y^{\prime}(0)=-10$
5. $y^{\prime\prime}-3y^{\prime}+2y=0$; $y_{1}=e^{x}$, $y_{2}=e^{2x}$; $y(0)=1$, $y^{\prime}(0)=0$
6. $y^{\prime\prime}+y^{\prime}-6y=0$; $y_{1}=e^{2x}$, $y_{2}=e^{-3x}$; $y(0)=7$, $y^{\prime}(0)=-1$
7. $y^{\prime\prime}+y^{\prime}=0$; $y_{1}=1$, $y_{2}=e^{-x}$; $y(0)=-2$, $y^{\prime}(0)=8$
8. $y^{\prime\prime}-3y^{\prime}=0$; $y_{1}=1$, $y_{2}=e^{3x}$; $y(0)=4$, $y^{\prime}(0)=-2$
9. $y^{\prime\prime}+2y^{\prime}+y=0$; $y_{1}=e^{-x}$, $y_{2}=xe^{-x}$; $y(0)=2$, $y^{\prime}(0)=-1$
10. $y^{\prime\prime}-10y^{\prime}+25y=0$; $y_{1}=e^{5x}$, $y_{2}=xe^{5x}$; $y(0)=3$, $y^{\prime}(0)=13$
11. $y^{\prime\prime}-2y^{\prime}+2y=0$; $y_{1}=e^{x}\cos x$, $y_{2}=e^{x}\sin x$; $y(0)=0$, $y^{\prime}(0)=5$
12. $y^{\prime\prime}+6y^{\prime}+13y=0$; $y_{1}=e^{-3x}\cos 2x$, $y_{2}=e^{-3x}\sin 2x$; $y(0)=2$, $y^{\prime}(0)=0$
13. $x^{2}y^{\prime\prime}-2xy^{\prime}+2y=0$; $y_{1}=x$, $y_{2}=x^{2}$; $y(1)=3$, $y^{\prime}(1)=1$
14. $x^{2}y^{\prime\prime}+2xy^{\prime}-6y=0$; $y_{1}=x^{2}$, $y_{2}=x^{-3}$; $y(2)=10$, $y^{\prime}(2)=15$
15. $x^{2}y^{\prime\prime}-xy^{\prime}+y=0$; $y_{1}=x$, $y_{2}=x \ln x$; $y(1)=7$, $y^{\prime}(1)=2$
16. $x^{2}y^{\prime\prime}+xy^{\prime}+y=0$; $y_{1}=\cos(\ln x)$, $y_{2}=\sin(\ln x)$; $y(1)=2$, $y^{\prime}(1)=3$

## Assignment 2: General Solutions
1. Let $y_{p}$ be a particular solution of the nonhomogeneous differential equation $y^{\prime\prime}+py^{\prime}+qy=f(x)$, and let $y_{c}$ be a solution of the associated homogeneous equation $y^{\prime\prime}+py^{\prime}+qy=0$. Show that $y=y_{c}+y_{p}$ is a solution of the given nonhomogeneous equation.
2. Let $y_{p}=1$ and $y_{c}=c_{1}\cos x+c_{2}\sin x$ as in previous problem. Find a solution of the equation $y^{\prime\prime}+y=1$ that satisfies the initial conditions $y(0)=-1$, $y^{\prime}(0)=1$.

## Assignment 3: Linear Independence
Instruction: Determine whether the following pairs of functions are linearly independent or linearly dependent on the real line. You may use the Wronskian function.
1. $f(x)=x$, $g(x)=\cos^{2}x+\sin^{2}x$
2. $f(x)=x^{3}$, $g(x)=x^{2}|x|$
3. $f(x)=1+x$, $g(x)=1+|x|$
4. $f(x)=xe^{x}$, $g(x)=|x|e^{x}$
5. $f(x)=\sin^{2}x$, $g(x)=1-\cos 2x$
6. $f(x)=e^{x}\sin x$, $g(x)=e^{x}\cos x$
7. $f(x)=2\cos x+3\sin x$, $g(x)=3\cos x-2\sin x$

## Assignment 4: Existence and Uniqueness
1. Show that $y_{1}=x^{2}$ and $y_{2}=x^{3}$ are two different solutions of $x^{2}y^{\prime\prime}-4xy^{\prime}+6y=0$, both satisfying the initial conditions $y(0)=0=y^{\prime}(0)$. Explain why these facts do not contradict Theorem 2.
2. (a) Show that $y_{1}=x^{3}$ and $y_{2}=|x^{3}|$ are linearly independent solutions on the real line of the equation $x^{2}y^{\prime\prime}-3xy^{\prime}+3y=0$. (b) Verify that the Wronskian $W(y_{1},y_{2})$ is identically zero. Explain why these facts do not contradict Theorem 3.
3. Show that $y_{1}=\sin(x^{2})$ and $y_{2}=\cos(x^{2})$ are linearly independent functions, but their Wronskian vanishes at $x=0$. Why does this imply that there is no differential equation of the form $y^{\prime\prime}+p(x)y^{\prime}+q(x)y=0$ with both $p$ and $q$ continuous everywhere, having both $y_{1}$ and $y_{2}$ as solutions?

## Assignment 5: Constant Coefficients
Instruction: Apply Theorems 5 and 6 to find general solutions.
1. $y^{\prime\prime}-3y^{\prime}+2y=0$
2. $y^{\prime\prime}+2y^{\prime}-15y=0$
3. $y^{\prime\prime}+5y^{\prime}=0$
4. $2y^{\prime\prime}+3y^{\prime}=0$
5. $2y^{\prime\prime}-y^{\prime}-y=0$
6. $4y^{\prime\prime}+8y^{\prime}+3y=0$
7. $4y^{\prime\prime}+4y^{\prime}+y=0$
8. $9y^{\prime\prime}-12y^{\prime}+4y=0$
9. $6y^{\prime\prime}-7y^{\prime}-20y=0$
10. $35y^{\prime\prime}-y^{\prime}-12y=0$

## Assignment 6: Finding Differential Equations
Instruction: Find the corresponding homogeneous second-order linear differential equation for the given general solution.
1. $y(x)=c_{1}+c_{2}e^{10x}$
2. $y(x)=c_{1}e^{10x}+c_{2}e^{-10x}$
3. $y(x)=c_{1}e^{10x}+c_{2}xe^{10x}$
4. $y(x)=c_{1}e^{10x}+c_{2}e^{100x}$
5. $y(x)=c_{1}+c_{2}x$
6. $y(x)=e^{x}(c_{1}e^{\sqrt{2}x}+c_{2}e^{-\sqrt{2}x})$

## Assignment 7: Linear Dependence
Instruction: Show directly that the given functions are linearly dependent by finding a nontrivial linear combination that vanishes identically.
1. $f(x)=2x$, $g(x)=3x^{2}$, $h(x)=5x-8x^{2}$
2. $f(x)=5$, $g(x)=2-3x^{2}$, $h(x)=10+15x^{2}$
3. $f(x)=0$, $g(x)=\sin x$, $h(x)=e^{x}$
4. $f(x)=17$, $g(x)=2\sin^{2}x$, $h(x)=3\cos^{2}x$
5. $f(x)=17$, $g(x)=\cos^{2}x$, $h(x)=\cos 2x$
6. $f(x)=e^{x}$, $g(x)=\cosh x$, $h(x)=\sinh x$

## Assignment 8: Linear Independence via Wronskian
Instruction: Use the Wronskian to prove linear independence on the indicated interval.
1. $f(x)=1$, $g(x)=x$, $h(x)=x^{2}$; Interval: $\mathbb{R}$
2. $f(x)=e^{x}$, $g(x)=e^{2x}$, $h(x)=e^{3x}$; Interval: $\mathbb{R}$
3. $f(x)=e^{x}$, $g(x)=\cos x$, $h(x)=\sin x$; Interval: $\mathbb{R}$
4. $f(x)=e^{x}$, $g(x)=x^{-2}$, $h(x)=x^{-2}\ln x$; Interval: $x>0$
5. $f(x)=x$, $g(x)=xe^{x}$, $h(x)=x^{2}e^{x}$; Interval: $\mathbb{R}$
6. $f(x)=x$, $g(x)=\cos(\ln x)$, $h(x)=\sin(\ln x)$; Interval: $x>0$

## Assignment 9: Higher-Order Homogeneous Equations
Instruction: Find a particular solution satisfying the initial conditions.
1. $y^{(3)}+2y^{\prime\prime}-y^{\prime}-2y=0$; $y(0)=1$, $y^{\prime}(0)=2$, $y^{\prime\prime}(0)=0$; Solutions: $e^{x}, e^{-x}, e^{-2x}$
2. $y^{(3)}-6y^{\prime\prime}+11y^{\prime}-6y=0$; $y(0)=0$, $y^{\prime}(0)=0$, $y^{\prime\prime}(0)=3$; Solutions: $e^{x}, e^{2x}, e^{3x}$
3. $y^{(3)}-3y^{\prime\prime}+3y^{\prime}-y=0$; $y(0)=2$, $y^{\prime}(0)=0$, $y^{\prime\prime}(0)=0$; Solutions: $e^{x}, xe^{x}, x^{2}e^{x}$
4. $y^{(3)}-5y^{\prime\prime}+8y^{\prime}-4y=0$; $y(0)=1$, $y^{\prime}(0)=4$, $y^{\prime\prime}(0)=0$; Solutions: $e^{x}, e^{2x}, xe^{2x}$
5. $y^{(3)}+9y^{\prime}=0$; $y(0)=3$, $y^{\prime}(0)=-1$, $y^{\prime\prime}(0)=2$; Solutions: $1, \cos(3x), \sin(3x)$
6. $y^{(3)}-3y^{\prime\prime}+4y^{\prime}-2y=0$; $y(0)=1, y^{\prime}(0)=0, y^{\prime\prime}(0)=0$; Solutions: $e^{x}, e^{x}\cos x, e^{x}\sin x$

## Assignment 10: Nonhomogeneous Equations
Instruction: Find a solution satisfying the given initial conditions.
1. $y^{\prime\prime}+y=3x$; $y(0)=2, y^{\prime}(0)=-2$; $y_{c}=c_{1}\cos x+c_{2}\sin x$, $y_{p}=3x$
2. $y^{\prime\prime}-4y=12$; $y(0)=0, y^{\prime}(0)=10$; $y_{c}=c_{1}e^{2x}+c_{2}e^{-2x}$, $y_{p}=-3$
3. $y^{\prime\prime}-2y^{\prime}-3y=6$; $y(0)=3, y^{\prime}(0)=11$; $y_{c}=c_{1}e^{-x}+c_{2}e^{3x}$, $y_{p}=-2$
4. $y^{\prime\prime}-2y^{\prime}+2y=2x$; $y(0)=4, y^{\prime}(0)=8$; $y_{c}=c_{1}e^{x}\cos x+c_{2}e^{x}\sin x$, $y_{p}=x+1$

## Assignment 11: General Solutions (Various Orders)
1. $y^{\prime\prime}-4y=0$
2. $2y^{\prime\prime}-3y^{\prime}=0$
3. $y^{\prime\prime}+3y^{\prime}-10y=0$
4. $2y^{\prime\prime}-7y^{\prime}+3y=0$
5. $y^{\prime\prime}+6y^{\prime}+9y=0$
6. $y^{\prime\prime}+5y^{\prime}+5y=0$
7. $4y^{\prime\prime}-12y^{\prime}+9y=0$
8. $y^{\prime\prime}-6y^{\prime}+13y=0$
9. $y^{\prime\prime}+8y^{\prime}+25y=0$
10. $5y^{(4)}+3y^{(3)}=0$
11. $y^{(4)}-8y^{(3)}+16y^{\prime\prime}=0$
12. $y^{(4)}-3y^{(3)}+3y^{\prime\prime}-y^{\prime}=0$
13. $9y^{(3)}+12y^{\prime\prime}+4y^{\prime}=0$
14. $y^{(4)}+3y^{\prime\prime}-4y=0$
15. $y^{(4)}-8y^{\prime\prime}+16y=0$
16. $y^{(4)}+18y^{\prime\prime}+81y=0$
17. $6y^{(4)}+11y^{\prime\prime}+4y=0$
18. $y^{(4)}=16y$
19. $y^{(3)}+y^{\prime\prime}-y^{\prime}-y=0$
20. $y^{(4)}+2y^{(3)}+3y^{\prime\prime}+2y^{\prime}+y=0$ (Suggestion: Expand $(r^{2}+r+1)^{2}$)

## Assignment 12: Initial Value Problems
1. $y^{\prime\prime}-4y^{\prime}+3y=0$; $y(0)=7, y^{\prime}(0)=11$
2. $9y^{\prime\prime}+6y^{\prime}+4y=0$; $y(0)=3, y^{\prime}(0)=4$
3. $y^{\prime\prime}-6y^{\prime}+25y=0$; $y(0)=3, y^{\prime}(0)=1$
4. $2y^{(3)}-3y^{\prime\prime}-2y^{\prime}=0$; $y(0)=1, y^{\prime}(0)=-1, y^{\prime\prime}(0)=3$
5. $3y^{(3)}+2y^{\prime\prime}=0$; $y(0)=-1, y^{\prime}(0)=0, y^{\prime\prime}(0)=1$
6. $y^{(3)}+10y^{\prime\prime}+25y^{\prime}=0$; $y(0)=3, y^{\prime}(0)=4, y^{\prime\prime}(0)=5$

## Assignment 13: Advanced Factoring and General Solutions
### Part A
Find an integral root by inspection, then factor by division.
1. $y^{(3)}+3y^{\prime\prime}-4y=0$
2. $y^{(3)}-y^{\prime\prime}-5y^{\prime}-2y=0$
3. $y^{(3)}+27y=0$
4. $y^{(4)}-y^{(3)}+y^{\prime\prime}-3y^{\prime}-6y=0$
5. $y^{(3)}+3y^{\prime\prime}+4y^{\prime}-8y=0$
6. $y^{(4)}+y^{(3)}-3y^{\prime\prime}-5y^{\prime}-2y=0$

### Part B
Find the general solution given one solution.
1. $y^{(3)}+3y^{\prime\prime}-54y=0$ with $y=e^{3x}$
2. $3y^{(3)}-2y^{\prime\prime}+12y^{\prime}-8y=0$ with $y=e^{2x/3}$
3. $6y^{(4)}+5y^{(3)}+25y^{\prime\prime}+20y^{\prime}+4y=0$ with $y=\cos 2x$
4. $9y^{(3)}+11y^{\prime\prime}+4y^{\prime}-14y=0$ with $y=e^{-x}\sin x$
5. Find $y(x)$ such that $y^{(4)}(x)=y(x)$, and $y(0)=18, y^{\prime}(0)=12, y^{\prime\prime}(0)=13, y^{(3)}(0)=7$.
6. Find a general solution of $y^{\prime\prime}-2iy^{\prime}+3y=0$.

## Assignment 14: Particular Solutions (Undetermined Coefficients)
Instruction: Find a particular solution $y_{p}$.
1. $y^{\prime\prime}+16y=e^{3x}$
2. $y^{\prime\prime}-y^{\prime}-2y=3x+4$
3. $y^{\prime\prime}-y^{\prime}-6y=2\sin 3x$
4. $4y^{\prime\prime}+4y^{\prime}+y=3xe^{x}$
5. $y^{\prime\prime}+y^{\prime}+y=\sin^{2}x$
6. $2y^{\prime\prime}+4y^{\prime}+7y=x^{2}$
7. $y^{\prime\prime}-4y=\sinh x$
8. $y^{\prime\prime}-4y=\cosh 2x$
9. $y^{\prime\prime}+2y^{\prime}-3y=1+xe^{x}$
10. $y^{\prime\prime}+9y=2\cos 3x+3\sin 3x$
11. $y^{(3)}+4y^{\prime}=3x-1$
12. $y^{(3)}+y^{\prime}=2\sin x$
13. $y^{\prime\prime}+2y^{\prime}+5y=e^{x}\sin x$
14. $y^{(4)}-2y^{\prime\prime}+y=xe^{x}$
15. $y^{(5)}+5y^{(4)}-y=17$
16. $y^{\prime\prime}+9y=2x^{2}e^{3x}+5$
17. $y^{\prime\prime}+y=\sin x+x\cos x$
18. $y^{(4)}-5y^{\prime\prime}+4y=e^{x}-xe^{2x}$
19. $y^{(5)}+2y^{(3)}+2y^{\prime\prime}=3x^{2}-1$
20. $y^{(3)}-y=e^{x}+7$

## Assignment 15: Setting up Forms of Particular Solutions
Instruction: Set up the appropriate form of $y_{p}$ (do NOT solve for coefficients).
1. $y^{\prime\prime}-2y^{\prime}+2y=e^{x}\sin x$
2. $y^{(5)}-y^{(3)}=e^{x}+2x^{2}-5$
3. $y^{\prime\prime}+4y=3x\cos 2x$
4. $y^{(3)}+y^{\prime\prime}-12y^{\prime}=x-2xe^{-3x}$
5. $y^{\prime\prime}+3y^{\prime}+2y=x(e^{x}-e^{-2x})$
6. $y^{\prime\prime}-6y^{\prime}+13y=xe^{3x}\sin 2x$
7. $y^{(4)}+5y^{\prime\prime}+4y=\sin x+\cos 2x$
8. $y^{(4)}+9y^{\prime\prime}=(x^{2}+1)\sin 3x$
9. $(D-\frac{1}{3})(D^{2}-4)y=xe^{x}+e^{2x}+e^{-2x}$
10. $y^{(4)}-2y^{\prime\prime}+y=x^{2}\cos x$

## Assignment 16: Solving Nonhomogeneous IVPs
1. $y^{\prime\prime}+4y=2x$; $y(0)=1, y^{\prime}(0)=2$
2. $y^{\prime\prime}+3y^{\prime}+2y=e^{x}$; $y(0)=0, y^{\prime}(0)=3$
3. $y^{\prime\prime}+9y=\sin 2x$; $y(0)=1, y^{\prime}(0)=0$
4. $y^{\prime\prime}+y=\cos x$; $y(0)=1, y^{\prime}(0)=-1$
5. $y^{\prime\prime}-2y^{\prime}+2y=x+1$; $y(0)=3, y^{\prime}(0)=0$
6. $y^{(4)}-4y^{\prime\prime}=x^{2}$; $y(0)=y^{\prime}(0)=y^{\prime\prime}(0)=y^{(3)}(0)=-1$
7. $y^{(3)}-2y^{\prime\prime}+y^{\prime}=1+xe^{x}$; $y(0)=y^{\prime}(0)=0, y^{\prime\prime}(0)=1$
8. $y^{\prime\prime}+2y^{\prime}+2y=\sin 3x$; $y(0)=2, y^{\prime}(0)=0$
9. $y^{(3)}+y^{\prime\prime}=x+e^{x}$; $y(0)=1, y^{\prime}(0)=0, y^{\prime\prime}(0)=1$
10. $y^{(4)}-y=5$; $y(0)=y^{\prime}(0)=y^{\prime\prime}(0)=y^{(3)}(0)=0$

## Assignment 17: Variation of Parameters
Instruction: Use the method of variation of parameters to find a particular solution.
1. $y^{\prime\prime}+3y^{\prime}+2y=4e^{x}$
2. $y^{\prime\prime}-2y^{\prime}-8y=3e^{-2x}$
3. $y^{\prime\prime}-4y^{\prime}+4y=2e^{2x}$
4. $y^{\prime\prime}-4y=\sinh 2x$
5. $y^{\prime\prime}+4y=\cos 3x$
6. $y^{\prime\prime}+9y=\sin 3x$
7. $y^{\prime\prime}+9y=2\sec 3x$
8. $y^{\prime\prime}+y=\csc^{2}x$
9. $y^{\prime\prime}+4y=\sin^{2}x$
10. $y^{\prime\prime}-4y=xe^{x}$