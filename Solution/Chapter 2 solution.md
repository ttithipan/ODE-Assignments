# Chapter 2 Solutions

## Assignment 1: Introduction to Second-Order Linear Equations

**Instruction:** First verify that $y_1$ and $y_2$ are solutions of the differential equation. Then find a particular solution of the form $y = c_1 y_1 + c_2 y_2$ that satisfies the given initial conditions.

---
**1.** $y^{\prime\prime}-y=0$; $y_{1}=e^{x}$, $y_{2}=e^{-x}$; $y(0)=0$, $y^{\prime}(0)=5$

**Verification:**
*   For $y_1 = e^x$: $y_1' = e^x$, $y_1'' = e^x$. Substitute into the DE: $e^x - e^x = 0$. True.
*   For $y_2 = e^{-x}$: $y_2' = -e^{-x}$, $y_2'' = e^{-x}$. Substitute into the DE: $e^{-x} - e^{-x} = 0$. True.

**Finding Particular Solution:**
The general solution is $y(x) = c_1 e^x + c_2 e^{-x}$.
Its derivative is $y'(x) = c_1 e^x - c_2 e^{-x}$.
Apply initial conditions:
1. $y(0) = c_1(1) + c_2(1) = 0 \implies c_1 + c_2 = 0$
2. $y'(0) = c_1(1) - c_2(1) = 5 \implies c_1 - c_2 = 5$
Adding the two equations: $2c_1 = 5 \implies c_1 = \frac{5}{2}$.
Subtracting the two equations: $2c_2 = -5 \implies c_2 = -\frac{5}{2}$.
**Final Answer:** $y(x) = \frac{5}{2}e^{x} - \frac{5}{2}e^{-x}$

---
**2.** $y^{\prime\prime}-9y=0$; $y_{1}=e^{3x}$, $y_{2}=e^{-3x}$; $y(0)=-1$, $y^{\prime}(0)=15$

**Verification:**
*   For $y_1 = e^{3x}$: $y_1' = 3e^{3x}$, $y_1'' = 9e^{3x}$. Substitute: $9e^{3x} - 9(e^{3x}) = 0$. True.
*   For $y_2 = e^{-3x}$: $y_2' = -3e^{-3x}$, $y_2'' = 9e^{-3x}$. Substitute: $9e^{-3x} - 9(e^{-3x}) = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 e^{3x} + c_2 e^{-3x}$
$y'(x) = 3c_1 e^{3x} - 3c_2 e^{-3x}$
Apply initial conditions:
1. $y(0) = c_1 + c_2 = -1$
2. $y'(0) = 3c_1 - 3c_2 = 15 \implies c_1 - c_2 = 5$
Adding the equations: $2c_1 = 4 \implies c_1 = 2$.
Substitute $c_1$: $2 + c_2 = -1 \implies c_2 = -3$.
**Final Answer:** $y(x) = 2e^{3x} - 3e^{-3x}$

---
**3.** $y^{\prime\prime}+4y=0$; $y_{1}=\cos 2x$, $y_{2}=\sin 2x$; $y(0)=3$, $y^{\prime}(0)=8$

**Verification:**
*   For $y_1 = \cos 2x$: $y_1' = -2\sin 2x$, $y_1'' = -4\cos 2x$. Substitute: $-4\cos 2x + 4(\cos 2x) = 0$. True.
*   For $y_2 = \sin 2x$: $y_2' = 2\cos 2x$, $y_2'' = -4\sin 2x$. Substitute: $-4\sin 2x + 4(\sin 2x) = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 \cos 2x + c_2 \sin 2x$
$y'(x) = -2c_1 \sin 2x + 2c_2 \cos 2x$
Apply initial conditions:
1. $y(0) = c_1(1) + c_2(0) = 3 \implies c_1 = 3$
2. $y'(0) = -2(3)(0) + 2c_2(1) = 8 \implies 2c_2 = 8 \implies c_2 = 4$
**Final Answer:** $y(x) = 3\cos 2x + 4\sin 2x$

---
**4.** $y^{\prime\prime}+25y=0$; $y_{1}=\cos 5x$, $y_{2}=\sin 5x$; $y(0)=10$, $y^{\prime}(0)=-10$

**Verification:**
*   For $y_1 = \cos 5x$: $y_1'' = -25\cos 5x$. Substitute: $-25\cos 5x + 25\cos 5x = 0$. True.
*   For $y_2 = \sin 5x$: $y_2'' = -25\sin 5x$. Substitute: $-25\sin 5x + 25\sin 5x = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 \cos 5x + c_2 \sin 5x$
$y'(x) = -5c_1 \sin 5x + 5c_2 \cos 5x$
Apply initial conditions:
1. $y(0) = c_1 = 10$
2. $y'(0) = 5c_2 = -10 \implies c_2 = -2$
**Final Answer:** $y(x) = 10\cos 5x - 2\sin 5x$

---
**5.** $y^{\prime\prime}-3y^{\prime}+2y=0$; $y_{1}=e^{x}$, $y_{2}=e^{2x}$; $y(0)=1$, $y^{\prime}(0)=0$

**Verification:**
*   For $y_1 = e^x$: $y_1' = e^x$, $y_1'' = e^x$. Substitute: $e^x - 3e^x + 2e^x = 0$. True.
*   For $y_2 = e^{2x}$: $y_2' = 2e^{2x}$, $y_2'' = 4e^{2x}$. Substitute: $4e^{2x} - 3(2e^{2x}) + 2e^{2x} = (4 - 6 + 2)e^{2x} = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 e^x + c_2 e^{2x}$
$y'(x) = c_1 e^x + 2c_2 e^{2x}$
Apply initial conditions:
1. $y(0) = c_1 + c_2 = 1$
2. $y'(0) = c_1 + 2c_2 = 0 \implies c_1 = -2c_2$
Substitute into first eq: $-2c_2 + c_2 = 1 \implies -c_2 = 1 \implies c_2 = -1$
Then $c_1 = -2(-1) = 2$.
**Final Answer:** $y(x) = 2e^{x} - e^{2x}$

---
**6.** $y^{\prime\prime}+y^{\prime}-6y=0$; $y_{1}=e^{2x}$, $y_{2}=e^{-3x}$; $y(0)=7$, $y^{\prime}(0)=-1$

**Verification:**
*   For $y_1 = e^{2x}$: $y_1' = 2e^{2x}$, $y_1'' = 4e^{2x}$. $4e^{2x} + 2e^{2x} - 6e^{2x} = 0$. True.
*   For $y_2 = e^{-3x}$: $y_2' = -3e^{-3x}$, $y_2'' = 9e^{-3x}$. $9e^{-3x} - 3e^{-3x} - 6e^{-3x} = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 e^{2x} + c_2 e^{-3x}$
$y'(x) = 2c_1 e^{2x} - 3c_2 e^{-3x}$
Apply initial conditions:
1. $y(0) = c_1 + c_2 = 7$
2. $y'(0) = 2c_1 - 3c_2 = -1$
Multiply first by 3: $3c_1 + 3c_2 = 21$. Add to second: $5c_1 = 20 \implies c_1 = 4$.
Then $c_2 = 7 - 4 = 3$.
**Final Answer:** $y(x) = 4e^{2x} + 3e^{-3x}$

---
**7.** $y^{\prime\prime}+y^{\prime}=0$; $y_{1}=1$, $y_{2}=e^{-x}$; $y(0)=-2$, $y^{\prime}(0)=8$

**Verification:**
*   For $y_1 = 1$: $y_1' = 0$, $y_1'' = 0$. $0 + 0 = 0$. True.
*   For $y_2 = e^{-x}$: $y_2' = -e^{-x}$, $y_2'' = e^{-x}$. $e^{-x} - e^{-x} = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1(1) + c_2 e^{-x} = c_1 + c_2 e^{-x}$
$y'(x) = -c_2 e^{-x}$
Apply initial conditions:
1. $y(0) = c_1 + c_2 = -2$
2. $y'(0) = -c_2 = 8 \implies c_2 = -8$
$c_1 - 8 = -2 \implies c_1 = 6$
**Final Answer:** $y(x) = 6 - 8e^{-x}$

---
**8.** $y^{\prime\prime}-3y^{\prime}=0$; $y_{1}=1$, $y_{2}=e^{3x}$; $y(0)=4$, $y^{\prime}(0)=-2$

**Verification:**
*   For $y_1 = 1$: $y_1' = 0$, $y_1'' = 0$. $0 - 3(0) = 0$. True.
*   For $y_2 = e^{3x}$: $y_2' = 3e^{3x}$, $y_2'' = 9e^{3x}$. $9e^{3x} - 3(3e^{3x}) = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 + c_2 e^{3x}$
$y'(x) = 3c_2 e^{3x}$
Apply initial conditions:
1. $y(0) = c_1 + c_2 = 4$
2. $y'(0) = 3c_2 = -2 \implies c_2 = -\frac{2}{3}$
$c_1 - \frac{2}{3} = 4 \implies c_1 = \frac{14}{3}$
**Final Answer:** $y(x) = \frac{14}{3} - \frac{2}{3}e^{3x}$

---
**9.** $y^{\prime\prime}+2y^{\prime}+y=0$; $y_{1}=e^{-x}$, $y_{2}=xe^{-x}$; $y(0)=2$, $y^{\prime}(0)=-1$

**Verification:**
*   For $y_1 = e^{-x}$: $y_1' = -e^{-x}$, $y_1'' = e^{-x}$. Substitute: $e^{-x} - 2e^{-x} + e^{-x} = 0$. True.
*   For $y_2 = xe^{-x}$: $y_2' = e^{-x} - xe^{-x}$, $y_2'' = -e^{-x} - (e^{-x} - xe^{-x}) = -2e^{-x} + xe^{-x}$. Substitute: $(-2e^{-x} + xe^{-x}) + 2(e^{-x} - xe^{-x}) + xe^{-x} = -2e^{-x} + xe^{-x} + 2e^{-x} - 2xe^{-x} + xe^{-x} = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 e^{-x} + c_2 xe^{-x}$
$y'(x) = -c_1 e^{-x} + c_2(e^{-x} - xe^{-x})$
Apply initial conditions:
1. $y(0) = c_1 = 2$
2. $y'(0) = -c_1 + c_2 = -1 \implies -2 + c_2 = -1 \implies c_2 = 1$
**Final Answer:** $y(x) = 2e^{-x} + xe^{-x}$

---
**10.** $y^{\prime\prime}-10y^{\prime}+25y=0$; $y_{1}=e^{5x}$, $y_{2}=xe^{5x}$; $y(0)=3$, $y^{\prime}(0)=13$

**Verification:**
*   For $y_1 = e^{5x}$: $y_1' = 5e^{5x}$, $y_1'' = 25e^{5x}$. $25e^{5x} - 10(5e^{5x}) + 25e^{5x} = 0$. True.
*   For $y_2 = xe^{5x}$: $y_2' = e^{5x} + 5xe^{5x}$, $y_2'' = 5e^{5x} + 5e^{5x} + 25xe^{5x} = 10e^{5x} + 25xe^{5x}$. Substitute: $(10e^{5x} + 25xe^{5x}) - 10(e^{5x} + 5xe^{5x}) + 25(xe^{5x}) = 10e^{5x} + 25xe^{5x} - 10e^{5x} - 50xe^{5x} + 25xe^{5x} = 0$. True.

**Finding Particular Solution:**
$y(x) = c_1 e^{5x} + c_2 xe^{5x}$
$y'(x) = 5c_1 e^{5x} + c_2(e^{5x} + 5xe^{5x})$
Apply initial conditions:
1. $y(0) = c_1 = 3$
2. $y'(0) = 5c_1 + c_2 = 13 \implies 5(3) + c_2 = 13 \implies 15 + c_2 = 13 \implies c_2 = -2$
**Final Answer:** $y(x) = 3e^{5x} - 2xe^{5x}$

## Assignment 5: Constant Coefficients

**Instruction:** Apply Theorems 5 and 6 to find general solutions.

**1.** $y''-3y'+2y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} - 3 r + 2 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 2$ with multiplicity 1.
- Root $r = 1$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{2x} + c_2  e^{1x}$

---
**2.** $y''+2y'-15y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} + 2 r - 15 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 3$ with multiplicity 1.
- Root $r = -5$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{3x} + c_2  e^{-5x}$

---
**3.** $y''+5y'=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} + 5 r = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = -5$ with multiplicity 1.
- Root $r = 0$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{-5x} + c_2  $

---
**4.** $2y''+3y'=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$2 r^{2} + 3 r = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{3}{2}$ with multiplicity 1.
- Root $r = 0$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{- \frac{3}{2}x} + c_2  $

---
**5.** $2y''-y'-y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$2 r^{2} - r - 1 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 1$ with multiplicity 1.
- Root $r = - \frac{1}{2}$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{1x} + c_2  e^{- \frac{1}{2}x}$

---
**6.** $4y''+8y'+3y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$4 r^{2} + 8 r + 3 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{1}{2}$ with multiplicity 1.
- Root $r = - \frac{3}{2}$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{- \frac{1}{2}x} + c_2  e^{- \frac{3}{2}x}$

---
**7.** $4y''+4y'+y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$4 r^{2} + 4 r + 1 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{1}{2}$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{- \frac{1}{2}x} + c_2 x e^{- \frac{1}{2}x}$

---
**8.** $9y''-12y'+4y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$9 r^{2} - 12 r + 4 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = \frac{2}{3}$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{\frac{2}{3}x} + c_2 x e^{\frac{2}{3}x}$

---
**9.** $6y''-7y'-20y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$6 r^{2} - 7 r - 20 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = \frac{5}{2}$ with multiplicity 1.
- Root $r = - \frac{4}{3}$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{\frac{5}{2}x} + c_2  e^{- \frac{4}{3}x}$

---
**10.** $35y''-y'-12y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$35 r^{2} - r - 12 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = \frac{3}{5}$ with multiplicity 1.
- Root $r = - \frac{4}{7}$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{\frac{3}{5}x} + c_2  e^{- \frac{4}{7}x}$

---

## Assignment 11: General Solutions (Various Orders)

**1.** $y''-4y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} - 4 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = -2$ with multiplicity 1.
- Root $r = 2$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{-2x} + c_2  e^{2x}$

---
**2.** $2y''-3y'=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$2 r^{2} - 3 r = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = \frac{3}{2}$ with multiplicity 1.
- Root $r = 0$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{\frac{3}{2}x} + c_2  $

---
**3.** $y''+3y'-10y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} + 3 r - 10 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 2$ with multiplicity 1.
- Root $r = -5$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{2x} + c_2  e^{-5x}$

---
**4.** $2y''-7y'+3y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$2 r^{2} - 7 r + 3 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 3$ with multiplicity 1.
- Root $r = \frac{1}{2}$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{3x} + c_2  e^{\frac{1}{2}x}$

---
**5.** $y''+6y'+9y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} + 6 r + 9 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = -3$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{-3x} + c_2 x e^{-3x}$

---
**6.** $y''+5y'+5y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} + 5 r + 5 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{5}{2} - \frac{\sqrt{5}}{2}$ with multiplicity 1.
- Root $r = - \frac{5}{2} + \frac{\sqrt{5}}{2}$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{- \frac{5}{2} - \frac{\sqrt{5}}{2}x} + c_2  e^{- \frac{5}{2} + \frac{\sqrt{5}}{2}x}$

---
**7.** $4y''-12y'+9y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$4 r^{2} - 12 r + 9 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = \frac{3}{2}$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{\frac{3}{2}x} + c_2 x e^{\frac{3}{2}x}$

---
**8.** $y''-6y'+13y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} - 6 r + 13 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 3 - 2 i$ with multiplicity 1.
- Root $r = 3 + 2 i$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{3x} \cos(2x) + c_2  e^{3x} \sin(2x)$

---
**9.** $y''+8y'+25y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{2} + 8 r + 25 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = -4 - 3 i$ with multiplicity 1.
- Root $r = -4 + 3 i$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{-4x} \cos(3x) + c_2  e^{-4x} \sin(3x)$

---
**10.** $5y^{(4)}+3y^{(3)}=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$5 r^{4} + 3 r^{3} = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{3}{5}$ with multiplicity 1.
- Root $r = 0$ with multiplicity 3.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{- \frac{3}{5}x} + c_2   + c_3 x  + c_4 xx $

---
**11.** $y^{(4)}-8y^{(3)}+16y''=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{4} - 8 r^{3} + 16 r^{2} = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 4$ with multiplicity 2.
- Root $r = 0$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{4x} + c_2 x e^{4x} + c_3   + c_4 x $

---
**12.** $y^{(4)}-3y^{(3)}+3y''-y'=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{4} - 3 r^{3} + 3 r^{2} - r = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 1$ with multiplicity 3.
- Root $r = 0$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{1x} + c_2 x e^{1x} + c_3 xx e^{1x} + c_4  $

---
**13.** $9y^{(3)}+12y''+4y'=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$9 r^{3} + 12 r^{2} + 4 r = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{2}{3}$ with multiplicity 2.
- Root $r = 0$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{- \frac{2}{3}x} + c_2 x e^{- \frac{2}{3}x} + c_3  $

---
**14.** $y^{(4)}+3y''-4y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{4} + 3 r^{2} - 4 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 1$ with multiplicity 1.
- Root $r = -1$ with multiplicity 1.
- Root $r = - 2 i$ with multiplicity 1.
- Root $r = 2 i$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{1x} + c_2  e^{-1x} + c_3   \cos(2x) + c_4   \sin(2x)$

---
**15.** $y^{(4)}-8y''+16y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{4} - 8 r^{2} + 16 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 2$ with multiplicity 2.
- Root $r = -2$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{2x} + c_2 x e^{2x} + c_3  e^{-2x} + c_4 x e^{-2x}$

---
**16.** $y^{(4)}+18y''+81y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{4} + 18 r^{2} + 81 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - 3 i$ with multiplicity 2.
- Root $r = 3 i$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1   \cos(3x) + c_2   \sin(3x) + c_3 x  \cos(3x) + c_4 x  \sin(3x)$

---
**17.** $6y^{(4)}+11y''+4y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$6 r^{4} + 11 r^{2} + 4 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{\sqrt{2} i}{2}$ with multiplicity 1.
- Root $r = \frac{\sqrt{2} i}{2}$ with multiplicity 1.
- Root $r = - \frac{2 \sqrt{3} i}{3}$ with multiplicity 1.
- Root $r = \frac{2 \sqrt{3} i}{3}$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1   \cos(\frac{\sqrt{2}}{2}x) + c_2   \sin(\frac{\sqrt{2}}{2}x) + c_3   \cos(\frac{2 \sqrt{3}}{3}x) + c_4   \sin(\frac{2 \sqrt{3}}{3}x)$

---
**18.** $y^{(4)}-16y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{4} - 16 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = -2$ with multiplicity 1.
- Root $r = 2$ with multiplicity 1.
- Root $r = - 2 i$ with multiplicity 1.
- Root $r = 2 i$ with multiplicity 1.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{-2x} + c_2  e^{2x} + c_3   \cos(2x) + c_4   \sin(2x)$

---
**19.** $y^{(3)}+y''-y'-y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{3} + r^{2} - r - 1 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = 1$ with multiplicity 1.
- Root $r = -1$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{1x} + c_2  e^{-1x} + c_3 x e^{-1x}$

---
**20.** $y^{(4)}+2y^{(3)}+3y''+2y'+y=0$

**Step 1: Characteristic Equation**
Substitute $y = e^{rx}$ into the differential equation to obtain the characteristic equation:
$r^{4} + 2 r^{3} + 3 r^{2} + 2 r + 1 = 0$

**Step 2: Find Roots**
Solving for $r$ gives:
- Root $r = - \frac{1}{2} - \frac{\sqrt{3} i}{2}$ with multiplicity 2.
- Root $r = - \frac{1}{2} + \frac{\sqrt{3} i}{2}$ with multiplicity 2.

**Step 3: General Solution**
Based on the roots, the general solution is:
$y(x) = c_1  e^{- \frac{1}{2}x} \cos(\frac{\sqrt{3}}{2}x) + c_2  e^{- \frac{1}{2}x} \sin(\frac{\sqrt{3}}{2}x) + c_3 x e^{- \frac{1}{2}x} \cos(\frac{\sqrt{3}}{2}x) + c_4 x e^{- \frac{1}{2}x} \sin(\frac{\sqrt{3}}{2}x)$

---


## Assignment 2: General Solutions

**1.** Let $y_{p}$ be a particular solution of the nonhomogeneous differential equation $y^{\prime\prime}+py^{\prime}+qy=f(x)$, and let $y_{c}$ be a solution of the associated homogeneous equation $y^{\prime\prime}+py^{\prime}+qy=0$. Show that $y=y_{c}+y_{p}$ is a solution of the given nonhomogeneous equation.

**Proof:**
Since $y_p$ is a solution to the nonhomogeneous equation, we have $y_p^{\prime\prime} + p y_p^\prime + q y_p = f(x)$.
Since $y_c$ is a solution to the homogeneous equation, we have $y_c^{\prime\prime} + p y_c^\prime + q y_c = 0$.
Now consider $y = y_c + y_p$. Let's substitute it into the left side of the differential equation:
$y^{\prime\prime} + p y^\prime + q y = (y_c + y_p)^{\prime\prime} + p(y_c + y_p)^\prime + q(y_c + y_p)$
By linearity of derivatives, this expands to:
$(y_c^{\prime\prime} + p y_c^\prime + q y_c) + (y_p^{\prime\prime} + p y_p^\prime + q y_p)$
Substitute the known values:
$(0) + (f(x)) = f(x)$.
Thus, $y = y_c + y_p$ satisfies the nonhomogeneous equation.

---
**2.** Let $y_{p}=1$ and $y_{c}=c_{1}\cos x+c_{2}\sin x$ as in previous problem. Find a solution of the equation $y^{\prime\prime}+y=1$ that satisfies the initial conditions $y(0)=-1$, $y^{\prime}(0)=1$.

**Solution:**
The general solution is $y(x) = y_c + y_p = c_1\cos x + c_2\sin x + 1$.
The derivative is $y'(x) = -c_1\sin x + c_2\cos x$.
Apply initial conditions:
1. $y(0) = c_1(1) + c_2(0) + 1 = -1 \implies c_1 + 1 = -1 \implies c_1 = -2$.
2. $y'(0) = -c_1(0) + c_2(1) = 1 \implies c_2 = 1$.
Substitute the constants back into the general solution:
**Final Answer:** $y(x) = -2\cos x + \sin x + 1$.

## Assignment 3: Linear Independence

**Instruction:** Determine whether the following pairs of functions are linearly independent or linearly dependent on the real line. You may use the Wronskian function.

---
**1.** $f(x)=x$, $g(x)=\cos^{2}x+\sin^{2}x$
Notice that $g(x) = 1$ for all $x$. Let's compute the Wronskian:
$W(f, g) = f(x)g'(x) - f'(x)g(x) = (x)(0) - (1)(1) = -1 \neq 0$.
**Answer:** Linearly independent.

---
**2.** $f(x)=x^{3}$, $g(x)=x^{2}|x|$
For $x \ge 0$, $g(x) = x^3$, thus $f(x) - g(x) = 0$.
For $x < 0$, $g(x) = -x^3$, thus $f(x) + g(x) = 0$.
A linear combination $c_1 f(x) + c_2 g(x) = 0$ must hold for *all* $x$ with the *same* constants $c_1, c_2$.
At $x=1$: $c_1(1) + c_2(1) = 0 \implies c_1 = -c_2$.
At $x=-1$: $c_1(-1) + c_2(-1) = 0 \implies -c_1 - c_2 = 0 \implies c_1 = -c_2$.
Since $c_1 = -c_2$ holds everywhere without requiring $c_1 = c_2 = 0$, pick $c_1=1, c_2=-1$. Then for $x>0$: $x^3 - x^3 = 0$. But for $x<0$: $x^3 - (-x^3) = 2x^3 \neq 0$. Thus no single non-zero pair $(c_1, c_2)$ works for the entire real line.
**Answer:** Linearly independent.

---
**3.** $f(x)=1+x$, $g(x)=1+|x|$
Let $c_1 f(x) + c_2 g(x) = 0$ for all $x$.
At $x=1$: $c_1(2) + c_2(2) = 0 \implies c_1 + c_2 = 0$.
At $x=-1$: $c_1(0) + c_2(2) = 0 \implies 2c_2 = 0 \implies c_2 = 0$.
From the first equation, $c_1 + 0 = 0 \implies c_1 = 0$.
Since $c_1 = c_2 = 0$ is the only solution, the functions are linearly independent.
**Answer:** Linearly independent.

---
**4.** $f(x)=xe^{x}$, $g(x)=|x|e^{x}$
Let $c_1 f(x) + c_2 g(x) = 0$ for all $x$.
At $x=1$: $c_1 e + c_2 e = 0 \implies c_1 + c_2 = 0$.
At $x=-1$: $-c_1 e^{-1} + c_2 e^{-1} = 0 \implies -c_1 + c_2 = 0$.
Adding the two equations: $2c_2 = 0 \implies c_2 = 0$, which implies $c_1 = 0$.
**Answer:** Linearly independent.

---
**5.** $f(x)=\sin^{2}x$, $g(x)=1-\cos 2x$
By the double-angle identity for cosine, $\cos 2x = 1 - 2\sin^2 x$.
Thus, $1 - \cos 2x = 1 - (1 - 2\sin^2 x) = 2\sin^2 x$.
We notice that $g(x) = 2f(x)$, which means $2f(x) - g(x) = 0$. This is a nontrivial linear combination that is zero everywhere.
**Answer:** Linearly dependent.

---
**6.** $f(x)=e^{x}\sin x$, $g(x)=e^{x}\cos x$
Compute the Wronskian $W(f, g)$:
$f'(x) = e^x\sin x + e^x\cos x$
$g'(x) = e^x\cos x - e^x\sin x$
$W(f,g) = f(x)g'(x) - f'(x)g(x)$
$= (e^x\sin x)(e^x\cos x - e^x\sin x) - (e^x\sin x + e^x\cos x)(e^x\cos x)$
$= e^{2x} (\sin x \cos x - \sin^2 x) - e^{2x} (\sin x \cos x + \cos^2 x)$
$= e^{2x} (-\sin^2 x - \cos^2 x) = -e^{2x} (\sin^2 x + \cos^2 x) = -e^{2x} \neq 0$.
**Answer:** Linearly independent.

---
**7.** $f(x)=2\cos x+3\sin x$, $g(x)=3\cos x-2\sin x$
Compute the Wronskian $W(f, g)$:
$f'(x) = -2\sin x + 3\cos x$
$g'(x) = -3\sin x - 2\cos x$
$W = f(x)g'(x) - f'(x)g(x)$
$= (2\cos x + 3\sin x)(-3\sin x - 2\cos x) - (-2\sin x + 3\cos x)(3\cos x - 2\sin x)$
$= -(2\cos x + 3\sin x)^2 - (3\cos x - 2\sin x)^2$
$= -(4\cos^2 x + 12\cos x \sin x + 9\sin^2 x) - (9\cos^2 x - 12\cos x \sin x + 4\sin^2 x)$
$= -(13\cos^2 x + 13\sin^2 x) = -13 \neq 0$.
**Answer:** Linearly independent.

## Assignment 4: Existence and Uniqueness

**1.** $x^2 y'' - 4xy' + 6y = 0$, $y(0)=0=y'(0)$.
**Verification:**
For $y_1 = x^2$: $y_1' = 2x, y_1'' = 2$. Substituting: $x^2(2) - 4x(2x) + 6(x^2) = 2x^2 - 8x^2 + 6x^2 = 0$. True. $y_1(0)=0, y_1'(0)=0$.
For $y_2 = x^3$: $y_2' = 3x^2, y_2'' = 6x$. Substituting: $x^2(6x) - 4x(3x^2) + 6(x^3) = 6x^3 - 12x^3 + 6x^3 = 0$. True. $y_2(0)=0, y_2'(0)=0$.
**Explanation:** Theorem 2 (Existence and Uniqueness) requires the differential equation to be written in standard form $y'' + p(x)y' + q(x)y = 0$. Here, $p(x) = -\frac{4}{x}$ and $q(x) = \frac{6}{x^2}$. Both $p(x)$ and $q(x)$ are discontinuous at $x=0$, so the theorem's hypotheses are not met for an initial point at $x_0 = 0$. Therefore, having multiple solutions does not contradict Theorem 2.

---
**2.** (a) $x^2 y'' - 3xy' + 3y = 0$, $y_1 = x^3$, $y_2 = |x^3|$.
By definitions of $y_1$ and $y_2$, $y_1 = y_2$ for $x \ge 0$ and $y_1 = -y_2$ for $x < 0$. No single set of constants works across the entire real line so they are linearly independent.
(b) Wronskian $W$:
For $x > 0$: $W(x^3, x^3) = 0$.
For $x < 0$: $W(x^3, -x^3) = 0$.
Thus $W(y_1, y_2) \equiv 0$.
**Explanation:** Theorem 3 states that linearly independent solutions of $L[y]=0$ have a non-vanishing Wronskian if $p$ and $q$ are continuous. Similar to problem 1, the standard form coefficients $p(x) = -\frac{3}{x}$ and $q(x) = \frac{3}{x^2}$ are discontinuous at $x=0$. Thus, the theorem does not apply and this is not a contradiction.

---
**3.** $y_1=\sin(x^2)$, $y_2=\cos(x^2)$.
Linear independence check via arbitrary zero Wronskian value is not sufficient, but evaluating $W$ reveals deeper structure.
$W = (\sin(x^2))(-2x\sin(x^2)) - (\cos(x^2))(2x\cos(x^2)) = -2x(\sin^2(x^2) + \cos^2(x^2)) = -2x$.
At $x=0$, $W(0) = 0$.
**Explanation:** If $y_1$ and $y_2$ were solutions to $y'' + p(x)y' + q(x)y = 0$ with continuous $p$ and $q$ everywhere, Abel's Identity dictates that the Wronskian is given by $W(x) = W(x_0)e^{-\int p(x)dx}$. This means the Wronskian is either identically zero everywhere or never zero anywhere. Since $W(0) = 0$ but $W(1) = -2 \neq 0$, it is impossible for both $p$ and $q$ to be continuous everywhere.

## Assignment 6: Finding Differential Equations

**Instruction:** Find the corresponding homogeneous second-order linear differential equation for the given general solution.

**1.** $y(x)=c_{1}+c_{2}e^{10x}$
Roots are $r_1=0$ and $r_2=10$.
Characteristic equation: $(r-0)(r-10) = r^2 - 10r = 0$.
**Differential Equation:** $y^{\prime\prime} - 10y^\prime = 0$.

**2.** $y(x)=c_{1}e^{10x}+c_{2}e^{-10x}$
Roots are $r_1=10$ and $r_2=-10$.
Characteristic equation: $(r-10)(r+10) = r^2 - 100 = 0$.
**Differential Equation:** $y^{\prime\prime} - 100y = 0$.

**3.** $y(x)=c_{1}e^{10x}+c_{2}xe^{10x}$
Root is $r=10$ with multiplicity 2 (repeated root).
Characteristic equation: $(r-10)^2 = r^2 - 20r + 100 = 0$.
**Differential Equation:** $y^{\prime\prime} - 20y^\prime + 100y = 0$.

**4.** $y(x)=c_{1}e^{10x}+c_{2}e^{100x}$
Roots are $r_1=10$ and $r_2=100$.
Characteristic equation: $(r-10)(r-100) = r^2 - 110r + 1000 = 0$.
**Differential Equation:** $y^{\prime\prime} - 110y^\prime + 1000y = 0$.

**5.** $y(x)=c_{1}+c_{2}x$
Root is $r=0$ with multiplicity 2.
Characteristic equation: $(r-0)^2 = r^2 = 0$.
**Differential Equation:** $y^{\prime\prime} = 0$.

**6.** $y(x)=e^{x}(c_{1}e^{\sqrt{2}x}+c_{2}e^{-\sqrt{2}x})$
Rewritten: $y(x) = c_1 e^{(1+\sqrt{2})x} + c_2 e^{(1-\sqrt{2})x}$.
Roots are $r_1=1+\sqrt{2}$ and $r_2=1-\sqrt{2}$.
Sum of roots: $2$. Product of roots: $(1)^2 - (\sqrt{2})^2 = 1 - 2 = -1$.
Characteristic equation: $r^2 - (\text{Sum})r + (\text{Product}) = r^2 - 2r - 1 = 0$.
**Differential Equation:** $y^{\prime\prime} - 2y^\prime - y = 0$.

## Assignment 7: Linear Dependence

**Instruction:** Show directly that the given functions are linearly dependent by finding a nontrivial linear combination that vanishes identically.

**1.** $f(x)=2x$, $g(x)=3x^2$, $h(x)=5x-8x^2$
Notice that $h(x)$ can be rewritten using $f(x)$ and $g(x)$.
$h(x) = \frac{5}{2}(2x) - \frac{8}{3}(3x^2) = \frac{5}{2}f(x) - \frac{8}{3}g(x)$.
Thus, $\frac{5}{2}f(x) - \frac{8}{3}g(x) - h(x) = 0$ is a nontrivial linear combination.
**Answer:** Linearly dependent.

**2.** $f(x)=5$, $g(x)=2-3x^2$, $h(x)=10+15x^2$
Observe that $15x^2$ is linked to $-3x^2 \times -5$.
$h(x) = 10 + (-5)(-3x^2) = 10 - 5(2 - 3x^2 - 2) = 10 - 5(g(x) - 2) = 10 - 5g(x) + 10 = 20 - 5g(x)$.
Also $20 = 4 \times 5 = 4f(x)$.
Therefore, $h(x) = 4f(x) - 5g(x)$, which rearranges to $4f(x) - 5g(x) - h(x) = 0$.
**Answer:** Linearly dependent.

**3.** $f(x)=0$, $g(x)=\sin x$, $h(x)=e^x$
Since $f(x) = 0$, any combination with a non-zero coefficient for $f(x)$ and zeros for the others works.
$1 \cdot f(x) + 0 \cdot g(x) + 0 \cdot h(x) = 0$.
This is a nontrivial linear combination (coefficients are not all zero).
**Answer:** Linearly dependent.

**4.** $f(x)=17$, $g(x)=2\sin^2x$, $h(x)=3\cos^2x$
We know $\sin^2 x + \cos^2 x = 1$.
$\frac{1}{2}g(x) + \frac{1}{3}h(x) = 1$.
Multiply by 17: $\frac{17}{2}g(x) + \frac{17}{3}h(x) = 17 = f(x)$.
Thus, $f(x) - \frac{17}{2}g(x) - \frac{17}{3}h(x) = 0$.
**Answer:** Linearly dependent.

**5.** $f(x)=17$, $g(x)=\cos^2x$, $h(x)=\cos 2x$
Using the double angle identity, $h(x) = 2\cos^2 x - 1 = 2g(x) - 1$.
Thus, $1 = 2g(x) - h(x)$.
Multiply by 17: $17 = 34g(x) - 17h(x) \implies f(x) = 34g(x) - 17h(x)$.
A nontrivial combination is $f(x) - 34g(x) + 17h(x) = 0$.
**Answer:** Linearly dependent.

**6.** $f(x)=e^x$, $g(x)=\cosh x$, $h(x)=\sinh x$
By definition of hyperbolic functions: $g(x) = \frac{e^x + e^{-x}}{2}$ and $h(x) = \frac{e^x - e^{-x}}{2}$.
$g(x) + h(x) = \frac{e^x + e^{-x} + e^x - e^{-x}}{2} = \frac{2e^x}{2} = e^x = f(x)$.
Thus, $f(x) - g(x) - h(x) = 0$.
**Answer:** Linearly dependent.

## Assignment 8: Linear Independence via Wronskian

**Instruction:** Use the Wronskian to prove linear independence on the indicated interval.

**1.** $f(x)=1$, $g(x)=x$, $h(x)=x^2$; Interval: $\mathbb{R}$
$W = f(g'h'' - h'g'') - g(f'h'' - h'f'') + h(f'g'' - g'f'')$
In matrix determinant form:
$W = \det \begin{pmatrix} 1 & x & x^2 \\ 0 & 1 & 2x \\ 0 & 0 & 2 \end{pmatrix} = 1 \cdot (1 \cdot 2 - 2x \cdot 0) = 2 \neq 0$.
**Answer:** Since $W \neq 0$, they are linearly independent everywhere.

**2.** $f(x)=e^x$, $g(x)=e^{2x}$, $h(x)=e^{3x}$; Interval: $\mathbb{R}$
$W = \det \begin{pmatrix} e^x & e^{2x} & e^{3x} \\ e^x & 2e^{2x} & 3e^{3x} \\ e^x & 4e^{2x} & 9e^{3x} \end{pmatrix} = e^x e^{2x} e^{3x} \det \begin{pmatrix} 1 & 1 & 1 \\ 1 & 2 & 3 \\ 1 & 4 & 9 \end{pmatrix} = e^{6x} [1(18-12) - 1(9-3) + 1(4-2)]$
$= e^{6x} [6 - 6 + 2] = 2e^{6x}$.
Since $2e^{6x}$ is never zero on $\mathbb{R}$, they are linearly independent.

**3.** $f(x)=e^x$, $g(x)=\cos x$, $h(x)=\sin x$; Interval: $\mathbb{R}$
Evaluate Wronskian at $x=0$:
$f(0)=1, f'(0)=1, f''(0)=1$
$g(0)=1, g'(0)=0, g''(0)=-1$
$h(0)=0, h'(0)=1, h''(0)=0$
$W(0) = \det \begin{pmatrix} 1 & 1 & 0 \\ 1 & 0 & 1 \\ 1 & -1 & 0 \end{pmatrix} = 1 \cdot (0 - (-1)) - 1 \cdot (0 - 1) + 0 = 1 + 1 = 2 \neq 0$.
Since $W(0) \neq 0$, the functions are linearly independent on $\mathbb{R}$.

**4.** $f(x)=e^x$, $g(x)=x^{-2}$, $h(x)=x^{-2}\ln x$; Interval: $x>0$
Evaluate Wronskian at $x=1$ (which is $>0$):
$f(1)=e, f'(1)=e, f''(1)=e$
$g(x) = x^{-2} \implies g'(x) = -2x^{-3}, g''(x) = 6x^{-4} \implies g(1)=1, g'(1)=-2, g''(1)=6$
$h(x) = x^{-2}\ln x \implies h'(x) = -2x^{-3}\ln x + x^{-3}, h''(x) = 6x^{-4}\ln x - 2x^{-4} - 3x^{-4} = 6x^{-4}\ln x - 5x^{-4}$
$h(1)=0, h'(1)=1, h''(1)=-5$.
$W(1) = \det \begin{pmatrix} e & 1 & 0 \\ e & -2 & 1 \\ e & 6 & -5 \end{pmatrix} = e \cdot (10 - 6) - 1 \cdot (-5e - e) = 4e + 6e = 10e \neq 0$.
Since $W(1) \neq 0$, they are linearly independent.

**5.** $f(x)=x$, $g(x)=xe^x$, $h(x)=x^2e^x$; Interval: $\mathbb{R}$
Evaluate Wronskian at $x=1$:
$f(1)=1, f'(1)=1, f''(1)=0$
$g(x)=xe^x \implies g'=e^x+xe^x, g''=2e^x+xe^x \implies g(1)=e, g'(1)=2e, g''(1)=3e$
$h(x)=x^2e^x \implies h'=2xe^x+x^2e^x, h''=2e^x+4xe^x+x^2e^x \implies h(1)=e, h'(1)=3e, h''(1)=7e$
$W(1) = \det \begin{pmatrix} 1 & e & e \\ 1 & 2e & 3e \\ 0 & 3e & 7e \end{pmatrix} = 1 \cdot (14e^2 - 9e^2) - e \cdot (7e - 0) + e \cdot (3e - 0) = 5e^2 - 7e^2 + 3e^2 = e^2 \neq 0$.
Since $W(1) \neq 0$, they are linearly independent.

**6.** $f(x)=x$, $g(x)=\cos(\ln x)$, $h(x)=\sin(\ln x)$; Interval: $x>0$
Evaluate Wronskian at $x=1$:
$f(1)=1, f'(1)=1, f''(1)=0$
$g(x)=\cos(\ln x) \implies g'(x)=-\frac{1}{x}\sin(\ln x), g''(x)=\frac{1}{x^2}\sin(\ln x) - \frac{1}{x^2}\cos(\ln x)$
$\implies g(1)=1, g'(1)=0, g''(1)=-1$
$h(x)=\sin(\ln x) \implies h'(x)=\frac{1}{x}\cos(\ln x), h''(x)=-\frac{1}{x^2}\cos(\ln x) - \frac{1}{x^2}\sin(\ln x)$
$\implies h(1)=0, h'(1)=1, h''(1)=-1$
$W(1) = \det \begin{pmatrix} 1 & 1 & 0 \\ 1 & 0 & 1 \\ 0 & -1 & -1 \end{pmatrix} = 1 \cdot (0 - (-1)) - 1 \cdot (-1 - 0) = 1 + 1 = 2 \neq 0$.
Since $W(1) \neq 0$, they are linearly independent.


## Assignment 9: Higher-Order Homogeneous Equations

**1.** $- 2 y{\left(x \right)} - \frac{d}{d x} y{\left(x \right)} + 2 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=1, y'(0)=2, y''(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{- x} + C_{3} e^{x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{4 e^{x}}{3} - \frac{e^{- 2 x}}{3}$

---
**2.** $- 6 y{\left(x \right)} + 11 \frac{d}{d x} y{\left(x \right)} - 6 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=0, y'(0)=0, y''(0)=3$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} e^{x} + C_{3} e^{2 x}\right) e^{x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(\frac{3 e^{2 x}}{2} - 3 e^{x} + \frac{3}{2}\right) e^{x}$

---
**3.** $- y{\left(x \right)} + 3 \frac{d}{d x} y{\left(x \right)} - 3 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=2, y'(0)=0, y''(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + x \left(C_{2} + C_{3} x\right)\right) e^{x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(x \left(x - 2\right) + 2\right) e^{x}$

---
**4.** $- 4 y{\left(x \right)} + 8 \frac{d}{d x} y{\left(x \right)} - 5 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=1, y'(0)=4, y''(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + \left(C_{2} + C_{3} x\right) e^{x}\right) e^{x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(\left(13 - 10 x\right) e^{x} - 12\right) e^{x}$

---
**5.** $9 \frac{d}{d x} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=3, y'(0)=-1, y''(0)=2$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} \sin{\left(3 x \right)} + C_{3} \cos{\left(3 x \right)}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = - \frac{\sin{\left(3 x \right)}}{3} - \frac{2 \cos{\left(3 x \right)}}{9} + \frac{29}{9}$

---
**6.** $- 2 y{\left(x \right)} + 4 \frac{d}{d x} y{\left(x \right)} - 3 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=1, y'(0)=0, y''(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} \sin{\left(x \right)} + C_{3} \cos{\left(x \right)}\right) e^{x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(- \sin{\left(x \right)} - \cos{\left(x \right)} + 2\right) e^{x}$

---

## Assignment 10: Nonhomogeneous Equations

**1.** $y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 3 x$

Initial conditions: $y(0)=2, y'(0)=-2$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = 3 x$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)} + 3 x$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = 3 x - 5 \sin{\left(x \right)} + 2 \cos{\left(x \right)}$

---
**2.** $- 4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 12$

Initial conditions: $y(0)=0, y'(0)=10$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = -3$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{2 x} - 3$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = 4 e^{2 x} - 3 - e^{- 2 x}$

---
**3.** $- 3 y{\left(x \right)} - 2 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 6$

Initial conditions: $y(0)=3, y'(0)=11$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- x} + C_{2} e^{3 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = -2$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- x} + C_{2} e^{3 x} - 2$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = 4 e^{3 x} - 2 + e^{- x}$

---
**4.** $2 y{\left(x \right)} - 2 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 2 x$

Initial conditions: $y(0)=4, y'(0)=8$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}\right) e^{x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = x + 1$

**Step 3: General Solution**
$y(x) = y_c + y_p = x + \left(C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}\right) e^{x} + 1$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = x + \left(4 \sin{\left(x \right)} + 3 \cos{\left(x \right)}\right) e^{x} + 1$

---

## Assignment 12: Initial Value Problems

**1.** $3 y{\left(x \right)} - 4 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=7, y'(0)=11$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} e^{2 x}\right) e^{x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(2 e^{2 x} + 5\right) e^{x}$

---
**2.** $4 y{\left(x \right)} + 6 \frac{d}{d x} y{\left(x \right)} + 9 \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=3, y'(0)=4$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(\frac{\sqrt{3} x}{3} \right)} + C_{2} \cos{\left(\frac{\sqrt{3} x}{3} \right)}\right) e^{- \frac{x}{3}}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(5 \sqrt{3} \sin{\left(\frac{\sqrt{3} x}{3} \right)} + 3 \cos{\left(\frac{\sqrt{3} x}{3} \right)}\right) e^{- \frac{x}{3}}$

---
**3.** $25 y{\left(x \right)} - 6 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=3, y'(0)=1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(4 x \right)} + C_{2} \cos{\left(4 x \right)}\right) e^{3 x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(- 2 \sin{\left(4 x \right)} + 3 \cos{\left(4 x \right)}\right) e^{3 x}$

---
**4.** $- 2 \frac{d}{d x} y{\left(x \right)} - 3 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + 2 \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=1, y'(0)=-1, y''(0)=3$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} e^{- \frac{x}{2}} + C_{3} e^{2 x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{e^{2 x}}{2} - \frac{7}{2} + 4 e^{- \frac{x}{2}}$

---
**5.** $2 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + 3 \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=-1, y'(0)=0, y''(0)=1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} x + C_{3} e^{- \frac{2 x}{3}}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{3 x}{2} - \frac{13}{4} + \frac{9 e^{- \frac{2 x}{3}}}{4}$

---
**6.** $25 \frac{d}{d x} y{\left(x \right)} + 10 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 0$

Initial conditions: $y(0)=3, y'(0)=4, y''(0)=5$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + \left(C_{2} + C_{3} x\right) e^{- 5 x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(- 5 x - \frac{9}{5}\right) e^{- 5 x} + \frac{24}{5}$

---

## Assignment 14: Particular Solutions (Undetermined Coefficients)

**Instruction:** Find a particular solution $y_p$.

**1.** $16 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = e^{3 x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(4 x \right)} + C_{2} \cos{\left(4 x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{e^{3 x}}{25}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} \sin{\left(4 x \right)} + C_{2} \cos{\left(4 x \right)} + \frac{e^{3 x}}{25}$

**Final Answer:** $y(x) = C_{1} \sin{\left(4 x \right)} + C_{2} \cos{\left(4 x \right)} + \frac{e^{3 x}}{25}$

---
**2.** $- 2 y{\left(x \right)} - \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 3 x + 4$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- x} + C_{2} e^{2 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{3 x}{2} - \frac{5}{4}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- x} + C_{2} e^{2 x} - \frac{3 x}{2} - \frac{5}{4}$

**Final Answer:** $y(x) = C_{1} e^{- x} + C_{2} e^{2 x} - \frac{3 x}{2} - \frac{5}{4}$

---
**3.** $- 6 y{\left(x \right)} - \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 2 \sin{\left(3 x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{3 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{5 \sin{\left(3 x \right)}}{39} + \frac{\cos{\left(3 x \right)}}{39}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{3 x} - \frac{5 \sin{\left(3 x \right)}}{39} + \frac{\cos{\left(3 x \right)}}{39}$

**Final Answer:** $y(x) = C_{1} e^{- 2 x} + C_{2} e^{3 x} - \frac{5 \sin{\left(3 x \right)}}{39} + \frac{\cos{\left(3 x \right)}}{39}$

---
**4.** $y{\left(x \right)} + 4 \frac{d}{d x} y{\left(x \right)} + 4 \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 3 x e^{x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} x\right) e^{- \frac{x}{2}}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{\left(3 x - 4\right) e^{x}}{9}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} + C_{2} x\right) e^{- \frac{x}{2}} + \frac{\left(3 x - 4\right) e^{x}}{9}$

**Final Answer:** $y(x) = \left(C_{1} + C_{2} x\right) e^{- \frac{x}{2}} + \frac{\left(3 x - 4\right) e^{x}}{9}$

---
**5.** $y{\left(x \right)} + \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \sin^{2}{\left(x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(\frac{\sqrt{3} x}{2} \right)} + C_{2} \cos{\left(\frac{\sqrt{3} x}{2} \right)}\right) e^{- \frac{x}{2}}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{\sin{\left(2 x \right)}}{13} + \frac{3 \cos{\left(2 x \right)}}{26} + \frac{1}{2}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} \sin{\left(\frac{\sqrt{3} x}{2} \right)} + C_{2} \cos{\left(\frac{\sqrt{3} x}{2} \right)}\right) e^{- \frac{x}{2}} - \frac{\sin{\left(2 x \right)}}{13} + \frac{3 \cos{\left(2 x \right)}}{26} + \frac{1}{2}$

**Final Answer:** $y(x) = \left(C_{1} \sin{\left(\frac{\sqrt{3} x}{2} \right)} + C_{2} \cos{\left(\frac{\sqrt{3} x}{2} \right)}\right) e^{- \frac{x}{2}} - \frac{\sin{\left(2 x \right)}}{13} + \frac{3 \cos{\left(2 x \right)}}{26} + \frac{1}{2}$

---
**6.** $7 y{\left(x \right)} + 4 \frac{d}{d x} y{\left(x \right)} + 2 \frac{d^{2}}{d x^{2}} y{\left(x \right)} = x^{2}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(\frac{\sqrt{10} x}{2} \right)} + C_{2} \cos{\left(\frac{\sqrt{10} x}{2} \right)}\right) e^{- x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x^{2}}{7} - \frac{8 x}{49} + \frac{4}{343}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \frac{x^{2}}{7} - \frac{8 x}{49} + \left(C_{1} \sin{\left(\frac{\sqrt{10} x}{2} \right)} + C_{2} \cos{\left(\frac{\sqrt{10} x}{2} \right)}\right) e^{- x} + \frac{4}{343}$

**Final Answer:** $y(x) = \frac{x^{2}}{7} - \frac{8 x}{49} + \left(C_{1} \sin{\left(\frac{\sqrt{10} x}{2} \right)} + C_{2} \cos{\left(\frac{\sqrt{10} x}{2} \right)}\right) e^{- x} + \frac{4}{343}$

---
**7.** $- 4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \sinh{\left(x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{\sinh{\left(x \right)}}{3}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{2 x} - \frac{\sinh{\left(x \right)}}{3}$

**Final Answer:** $y(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x} - \frac{\sinh{\left(x \right)}}{3}$

---
**8.** $- 4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \cosh{\left(2 x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x \sinh{\left(2 x \right)}}{4}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{2 x} + \frac{x \sinh{\left(2 x \right)}}{4}$

**Final Answer:** $y(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x} + \frac{x \sinh{\left(2 x \right)}}{4}$

---
**9.** $- 3 y{\left(x \right)} + 2 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = x e^{x} + 1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 3 x} + C_{2} e^{x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \left(\frac{x^{2}}{8} - \frac{x}{16}\right) e^{x} - \frac{1}{3}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{2} e^{- 3 x} + \left(C_{1} + \frac{x^{2}}{8} - \frac{x}{16}\right) e^{x} - \frac{1}{3}$

**Final Answer:** $y(x) = C_{2} e^{- 3 x} + \left(C_{1} + \frac{x^{2}}{8} - \frac{x}{16}\right) e^{x} - \frac{1}{3}$

---
**10.** $9 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 3 \sin{\left(3 x \right)} + 2 \cos{\left(3 x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x \sin{\left(3 x \right)}}{3} - \frac{x \cos{\left(3 x \right)}}{2}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} - \frac{x}{2}\right) \cos{\left(3 x \right)} + \left(C_{2} + \frac{x}{3}\right) \sin{\left(3 x \right)}$

**Final Answer:** $y(x) = \left(C_{1} - \frac{x}{2}\right) \cos{\left(3 x \right)} + \left(C_{2} + \frac{x}{3}\right) \sin{\left(3 x \right)}$

---
**11.** $4 \frac{d}{d x} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 3 x - 1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} \sin{\left(2 x \right)} + C_{3} \cos{\left(2 x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{3 x^{2}}{8} - \frac{x}{4}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} + C_{2} \sin{\left(2 x \right)} + C_{3} \cos{\left(2 x \right)} + \frac{3 x^{2}}{8} - \frac{x}{4}$

**Final Answer:** $y(x) = C_{1} + C_{2} \sin{\left(2 x \right)} + C_{3} \cos{\left(2 x \right)} + \frac{3 x^{2}}{8} - \frac{x}{4}$

---
**12.** $\frac{d}{d x} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = 2 \sin{\left(x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} \sin{\left(x \right)} + C_{3} \cos{\left(x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - x \sin{\left(x \right)}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} + C_{3} \cos{\left(x \right)} + \left(C_{2} - x\right) \sin{\left(x \right)}$

**Final Answer:** $y(x) = C_{1} + C_{3} \cos{\left(x \right)} + \left(C_{2} - x\right) \sin{\left(x \right)}$

---
**13.** $5 y{\left(x \right)} + 2 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = e^{x} \sin{\left(x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)}\right) e^{- x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{\left(7 \sin{\left(x \right)} - 4 \cos{\left(x \right)}\right) e^{x}}{65}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)}\right) e^{- x} + \frac{\left(7 \sin{\left(x \right)} - 4 \cos{\left(x \right)}\right) e^{x}}{65}$

**Final Answer:** $y(x) = \left(C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)}\right) e^{- x} + \frac{\left(7 \sin{\left(x \right)} - 4 \cos{\left(x \right)}\right) e^{x}}{65}$

---
**14.** $y{\left(x \right)} - 2 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{4}}{d x^{4}} y{\left(x \right)} = x e^{x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} x\right) e^{- x} + \left(C_{3} + C_{4} x\right) e^{x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = x \left(\frac{x^{2}}{24} - \frac{x}{8}\right) e^{x}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} + C_{2} x\right) e^{- x} + \left(C_{3} + x \left(C_{4} + \frac{x^{2}}{24} - \frac{x}{8}\right)\right) e^{x}$

**Final Answer:** $y(x) = \left(C_{1} + C_{2} x\right) e^{- x} + \left(C_{3} + x \left(C_{4} + \frac{x^{2}}{24} - \frac{x}{8}\right)\right) e^{x}$

---
**15.** $- y{\left(x \right)} + 5 \frac{d^{4}}{d x^{4}} y{\left(x \right)} + \frac{d^{5}}{d x^{5}} y{\left(x \right)} = 17$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{3} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 0\right)}} + C_{4} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 1\right)}} + C_{5} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 2\right)}} + \left(C_{1} \sin{\left(x \operatorname{im}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)} \right)} + C_{2} \cos{\left(x \operatorname{im}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)} \right)}\right) e^{x \operatorname{re}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)}}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = -17$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{3} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 0\right)}} + C_{4} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 1\right)}} + C_{5} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 2\right)}} + \left(C_{1} \sin{\left(x \operatorname{im}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)} \right)} + C_{2} \cos{\left(x \operatorname{im}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)} \right)}\right) e^{x \operatorname{re}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)}} - 17$

**Final Answer:** $y(x) = C_{3} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 0\right)}} + C_{4} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 1\right)}} + C_{5} e^{x \operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 2\right)}} + \left(C_{1} \sin{\left(x \operatorname{im}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)} \right)} + C_{2} \cos{\left(x \operatorname{im}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)} \right)}\right) e^{x \operatorname{re}{\left(\operatorname{CRootOf} {\left(x^{5} + 5 x^{4} - 1, 3\right)}\right)}} - 17$

---
**16.** $9 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 2 x^{2} e^{3 x} + 5$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x^{2} e^{3 x}}{9} - \frac{2 x e^{3 x}}{27} + \frac{e^{3 x}}{81} + \frac{5}{9}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)} + \frac{x^{2} e^{3 x}}{9} - \frac{2 x e^{3 x}}{27} + \frac{e^{3 x}}{81} + \frac{5}{9}$

**Final Answer:** $y(x) = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)} + \frac{x^{2} e^{3 x}}{9} - \frac{2 x e^{3 x}}{27} + \frac{e^{3 x}}{81} + \frac{5}{9}$

---
**17.** $y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = x \cos{\left(x \right)} + \sin{\left(x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x^{2} \sin{\left(x \right)}}{4} - \frac{x \cos{\left(x \right)}}{4}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} - \frac{x}{4}\right) \cos{\left(x \right)} + \left(C_{2} + \frac{x^{2}}{4}\right) \sin{\left(x \right)}$

**Final Answer:** $y(x) = \left(C_{1} - \frac{x}{4}\right) \cos{\left(x \right)} + \left(C_{2} + \frac{x^{2}}{4}\right) \sin{\left(x \right)}$

---
**18.** $4 y{\left(x \right)} - 5 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{4}}{d x^{4}} y{\left(x \right)} = - x e^{2 x} + e^{x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{- x} + C_{3} e^{x} + C_{4} e^{2 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{x e^{x}}{6} + \left(- \frac{x^{2}}{24} + \frac{19 x}{144}\right) e^{2 x}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{3} e^{- 2 x} + C_{4} e^{- x} + \left(C_{1} - \frac{x}{6}\right) e^{x} + \left(C_{2} - \frac{x^{2}}{24} + \frac{19 x}{144}\right) e^{2 x}$

**Final Answer:** $y(x) = C_{3} e^{- 2 x} + C_{4} e^{- x} + \left(C_{1} - \frac{x}{6}\right) e^{x} + \left(C_{2} - \frac{x^{2}}{24} + \frac{19 x}{144}\right) e^{2 x}$

---
**19.** $2 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + 2 \frac{d^{3}}{d x^{3}} y{\left(x \right)} + \frac{d^{5}}{d x^{5}} y{\left(x \right)} = 3 x^{2} - 1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} x + C_{3} e^{- \frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{6}} \sin{\left(\sqrt[6]{3} x \left(\frac{1}{\sqrt[3]{9 + \sqrt{105}}} + \frac{3^{\frac{2}{3}} \sqrt[3]{9 + \sqrt{105}}}{6}\right) \right)} + C_{4} e^{- \frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{6}} \cos{\left(\sqrt[6]{3} x \left(\frac{1}{\sqrt[3]{9 + \sqrt{105}}} + \frac{3^{\frac{2}{3}} \sqrt[3]{9 + \sqrt{105}}}{6}\right) \right)} + C_{5} e^{\frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{3}}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x^{4}}{8} - \frac{x^{3}}{2} + \frac{5 x^{2}}{4}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} + C_{2} x + C_{3} e^{- \frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{6}} \sin{\left(\sqrt[6]{3} x \left(\frac{1}{\sqrt[3]{9 + \sqrt{105}}} + \frac{3^{\frac{2}{3}} \sqrt[3]{9 + \sqrt{105}}}{6}\right) \right)} + C_{4} e^{- \frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{6}} \cos{\left(\sqrt[6]{3} x \left(\frac{1}{\sqrt[3]{9 + \sqrt{105}}} + \frac{3^{\frac{2}{3}} \sqrt[3]{9 + \sqrt{105}}}{6}\right) \right)} + C_{5} e^{\frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{3}} + \frac{x^{4}}{8} - \frac{x^{3}}{2} + \frac{5 x^{2}}{4}$

**Final Answer:** $y(x) = C_{1} + C_{2} x + C_{3} e^{- \frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{6}} \sin{\left(\sqrt[6]{3} x \left(\frac{1}{\sqrt[3]{9 + \sqrt{105}}} + \frac{3^{\frac{2}{3}} \sqrt[3]{9 + \sqrt{105}}}{6}\right) \right)} + C_{4} e^{- \frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{6}} \cos{\left(\sqrt[6]{3} x \left(\frac{1}{\sqrt[3]{9 + \sqrt{105}}} + \frac{3^{\frac{2}{3}} \sqrt[3]{9 + \sqrt{105}}}{6}\right) \right)} + C_{5} e^{\frac{\sqrt[3]{3} x \left(- \sqrt[3]{9 + \sqrt{105}} + \frac{2 \sqrt[3]{3}}{\sqrt[3]{9 + \sqrt{105}}}\right)}{3}} + \frac{x^{4}}{8} - \frac{x^{3}}{2} + \frac{5 x^{2}}{4}$

---
**20.** $- y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = e^{x} + 7$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{3} e^{x} + \left(C_{1} \sin{\left(\frac{\sqrt{3} x}{2} \right)} + C_{2} \cos{\left(\frac{\sqrt{3} x}{2} \right)}\right) e^{- \frac{x}{2}}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x e^{x}}{3} - 7$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} + \frac{x}{3}\right) e^{x} + \left(C_{2} \sin{\left(\frac{\sqrt{3} x}{2} \right)} + C_{3} \cos{\left(\frac{\sqrt{3} x}{2} \right)}\right) e^{- \frac{x}{2}} - 7$

**Final Answer:** $y(x) = \left(C_{1} + \frac{x}{3}\right) e^{x} + \left(C_{2} \sin{\left(\frac{\sqrt{3} x}{2} \right)} + C_{3} \cos{\left(\frac{\sqrt{3} x}{2} \right)}\right) e^{- \frac{x}{2}} - 7$

---

## Assignment 16: Solving Nonhomogeneous IVPs

**1.** $4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 2 x$

Initial conditions: $y(0)=1, y'(0)=2$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x}{2}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)} + \frac{x}{2}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{x}{2} + \frac{3 \sin{\left(2 x \right)}}{4} + \cos{\left(2 x \right)}$

---
**2.** $2 y{\left(x \right)} + 3 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = e^{x}$

Initial conditions: $y(0)=0, y'(0)=3$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} e^{- x}\right) e^{- x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{e^{x}}{6}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{- x} + \frac{e^{x}}{6}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{e^{x}}{6} + \frac{5 e^{- x}}{2} - \frac{8 e^{- 2 x}}{3}$

---
**3.** $9 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \sin{\left(2 x \right)}$

Initial conditions: $y(0)=1, y'(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{\sin{\left(2 x \right)}}{5}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)} + \frac{\sin{\left(2 x \right)}}{5}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{\sin{\left(2 x \right)}}{5} - \frac{2 \sin{\left(3 x \right)}}{15} + \cos{\left(3 x \right)}$

---
**4.** $y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \cos{\left(x \right)}$

Initial conditions: $y(0)=1, y'(0)=-1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x \sin{\left(x \right)}}{2}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{2} \cos{\left(x \right)} + \left(C_{1} + \frac{x}{2}\right) \sin{\left(x \right)}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(\frac{x}{2} - 1\right) \sin{\left(x \right)} + \cos{\left(x \right)}$

---
**5.** $2 y{\left(x \right)} - 2 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = x + 1$

Initial conditions: $y(0)=3, y'(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}\right) e^{x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x}{2} + 1$

**Step 3: General Solution**
$y(x) = y_c + y_p = \frac{x}{2} + \left(C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}\right) e^{x} + 1$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{x}{2} + \left(- \frac{5 \sin{\left(x \right)}}{2} + 2 \cos{\left(x \right)}\right) e^{x} + 1$

---
**6.** $- 4 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{4}}{d x^{4}} y{\left(x \right)} = x^{2}$

Initial conditions: $y(0)=-1, y'(0)=-1, y''(0)=-1, y^3(0)=-1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} x + C_{3} e^{- 2 x} + C_{4} e^{2 x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{x^{4}}{48} - \frac{x^{2}}{16}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} + C_{2} x + C_{3} e^{- 2 x} + C_{4} e^{2 x} - \frac{x^{4}}{48} - \frac{x^{2}}{16}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = - \frac{x^{4}}{48} - \frac{x^{2}}{16} - \frac{3 x}{4} - \frac{11 e^{2 x}}{64} - \frac{25}{32} - \frac{3 e^{- 2 x}}{64}$

---
**7.** $\frac{d}{d x} y{\left(x \right)} - 2 \frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = x e^{x} + 1$

Initial conditions: $y(0)=0, y'(0)=0, y''(0)=1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + \left(C_{2} + C_{3} x\right) e^{x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = x \left(\frac{x^{2}}{6} - \frac{x}{2}\right) e^{x} + x$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} + x + \left(C_{2} + x \left(C_{3} + \frac{x^{2}}{6} - \frac{x}{2}\right)\right) e^{x}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = x + \left(x \left(\frac{x^{2}}{6} - \frac{x}{2} + 3\right) - 4\right) e^{x} + 4$

---
**8.** $2 y{\left(x \right)} + 2 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \sin{\left(3 x \right)}$

Initial conditions: $y(0)=2, y'(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}\right) e^{- x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{7 \sin{\left(3 x \right)}}{85} - \frac{6 \cos{\left(3 x \right)}}{85}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}\right) e^{- x} - \frac{7 \sin{\left(3 x \right)}}{85} - \frac{6 \cos{\left(3 x \right)}}{85}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \left(\frac{197 \sin{\left(x \right)}}{85} + \frac{176 \cos{\left(x \right)}}{85}\right) e^{- x} - \frac{7 \sin{\left(3 x \right)}}{85} - \frac{6 \cos{\left(3 x \right)}}{85}$

---
**9.** $\frac{d^{2}}{d x^{2}} y{\left(x \right)} + \frac{d^{3}}{d x^{3}} y{\left(x \right)} = x + e^{x}$

Initial conditions: $y(0)=1, y'(0)=0, y''(0)=1$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} + C_{2} x + C_{3} e^{- x}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x^{3}}{6} - \frac{x^{2}}{2} + \frac{e^{x}}{2}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} + C_{2} x + C_{3} e^{- x} + \frac{x^{3}}{6} - \frac{x^{2}}{2} + \frac{e^{x}}{2}$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{x^{3}}{6} - \frac{x^{2}}{2} + x + \frac{e^{x}}{2} - 1 + \frac{3 e^{- x}}{2}$

---
**10.** $- y{\left(x \right)} + \frac{d^{4}}{d x^{4}} y{\left(x \right)} = 5$

Initial conditions: $y(0)=0, y'(0)=0, y''(0)=0, y^3(0)=0$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- x} + C_{2} e^{x} + C_{3} \sin{\left(x \right)} + C_{4} \cos{\left(x \right)}$

**Step 2: Particular Solution**
Using Undetermined Coefficients, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = -5$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- x} + C_{2} e^{x} + C_{3} \sin{\left(x \right)} + C_{4} \cos{\left(x \right)} - 5$

**Step 4: Apply Initial Conditions**
Substituting the initial conditions to solve for constants gives:
**Final Answer:** $y(x) = \frac{5 e^{x}}{4} + \frac{5 \cos{\left(x \right)}}{2} - 5 + \frac{5 e^{- x}}{4}$

---

## Assignment 17: Variation of Parameters

**1.** $2 y{\left(x \right)} + 3 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 4 e^{x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} e^{- x}\right) e^{- x}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{2 e^{x}}{3}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{- x} + \frac{2 e^{x}}{3}$

**Final Answer:** $y(x) = C_{1} e^{- 2 x} + C_{2} e^{- x} + \frac{2 e^{x}}{3}$

---
**2.** $- 8 y{\left(x \right)} - 2 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 3 e^{- 2 x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{4 x}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{x e^{- 2 x}}{2}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{2} e^{4 x} + \left(C_{1} - \frac{x}{2}\right) e^{- 2 x}$

**Final Answer:** $y(x) = C_{2} e^{4 x} + \left(C_{1} - \frac{x}{2}\right) e^{- 2 x}$

---
**3.** $4 y{\left(x \right)} - 4 \frac{d}{d x} y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 2 e^{2 x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = \left(C_{1} + C_{2} x\right) e^{2 x}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = x^{2} e^{2 x}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} + x \left(C_{2} + x\right)\right) e^{2 x}$

**Final Answer:** $y(x) = \left(C_{1} + x \left(C_{2} + x\right)\right) e^{2 x}$

---
**4.** $- 4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \sinh{\left(2 x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{x \cosh{\left(2 x \right)}}{4}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{2 x} + \frac{x \cosh{\left(2 x \right)}}{4}$

**Final Answer:** $y(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x} + \frac{x \cosh{\left(2 x \right)}}{4}$

---
**5.** $4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \cos{\left(3 x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{\cos{\left(3 x \right)}}{5}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)} - \frac{\cos{\left(3 x \right)}}{5}$

**Final Answer:** $y(x) = C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)} - \frac{\cos{\left(3 x \right)}}{5}$

---
**6.** $9 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \sin{\left(3 x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{x \cos{\left(3 x \right)}}{6}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{2} \sin{\left(3 x \right)} + \left(C_{1} - \frac{x}{6}\right) \cos{\left(3 x \right)}$

**Final Answer:** $y(x) = C_{2} \sin{\left(3 x \right)} + \left(C_{1} - \frac{x}{6}\right) \cos{\left(3 x \right)}$

---
**7.** $9 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = 2 \sec{\left(3 x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(3 x \right)} + C_{2} \cos{\left(3 x \right)}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \frac{2 x \sin{\left(3 x \right)}}{3} + \frac{2 \log{\left(\cos{\left(3 x \right)} \right)} \cos{\left(3 x \right)}}{9}$

**Step 3: General Solution**
$y(x) = y_c + y_p = \left(C_{1} + \frac{2 x}{3}\right) \sin{\left(3 x \right)} + \left(C_{2} + \frac{2 \log{\left(\cos{\left(3 x \right)} \right)}}{9}\right) \cos{\left(3 x \right)}$

**Final Answer:** $y(x) = \left(C_{1} + \frac{2 x}{3}\right) \sin{\left(3 x \right)} + \left(C_{2} + \frac{2 \log{\left(\cos{\left(3 x \right)} \right)}}{9}\right) \cos{\left(3 x \right)}$

---
**8.** $y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \csc^{2}{\left(x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(x \right)} + C_{2} \cos{\left(x \right)}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = \left(- \frac{\log{\left(\cos{\left(x \right)} - 1 \right)}}{2} + \frac{\log{\left(\cos{\left(x \right)} + 1 \right)}}{2}\right) \cos{\left(x \right)} - 1$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{2} \sin{\left(x \right)} + \left(C_{1} - \frac{\log{\left(\cos{\left(x \right)} - 1 \right)}}{2} + \frac{\log{\left(\cos{\left(x \right)} + 1 \right)}}{2}\right) \cos{\left(x \right)} - 1$

**Final Answer:** $y(x) = C_{2} \sin{\left(x \right)} + \left(C_{1} - \frac{\log{\left(\cos{\left(x \right)} - 1 \right)}}{2} + \frac{\log{\left(\cos{\left(x \right)} + 1 \right)}}{2}\right) \cos{\left(x \right)} - 1$

---
**9.** $4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = \sin^{2}{\left(x \right)}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} \sin{\left(2 x \right)} + C_{2} \cos{\left(2 x \right)}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{x \sin{\left(2 x \right)}}{8} + \frac{1}{8}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{2} \cos{\left(2 x \right)} + \left(C_{1} - \frac{x}{8}\right) \sin{\left(2 x \right)} + \frac{1}{8}$

**Final Answer:** $y(x) = C_{2} \cos{\left(2 x \right)} + \left(C_{1} - \frac{x}{8}\right) \sin{\left(2 x \right)} + \frac{1}{8}$

---
**10.** $- 4 y{\left(x \right)} + \frac{d^{2}}{d x^{2}} y{\left(x \right)} = x e^{x}$

**Step 1: Homogeneous Solution**
The solution to the associated homogeneous equation is:
$y_c(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x}$

**Step 2: Particular Solution**
Using Variation of Parameters, we find a particular solution $y_p$ for the nonhomogeneous part.
$y_p(x) = - \frac{x e^{x}}{3} - \frac{2 e^{x}}{9}$

**Step 3: General Solution**
$y(x) = y_c + y_p = C_{1} e^{- 2 x} + C_{2} e^{2 x} - \frac{x e^{x}}{3} - \frac{2 e^{x}}{9}$

**Final Answer:** $y(x) = C_{1} e^{- 2 x} + C_{2} e^{2 x} - \frac{x e^{x}}{3} - \frac{2 e^{x}}{9}$

---

## Assignment 13: Advanced Factoring and General Solutions

### Part A
**Instruction:** Find an integral root by inspection, then factor by division.

**1.** $y^{(3)}+3y^{\prime\prime}-4y=0$

The characteristic equation is $P(r) = r^{3} + 3 r^{2} - 4 = 0$.
By inspection, $r = 1$ is an integral root.
Factoring the polynomial gives: $\left(r - 1\right) \left(r + 2\right)^{2} = 0$.
The roots are: $1, -2$.
**General Solution:** $y(x) = c_1  e^{1x} + c_2  e^{-2x} + c_3 x e^{-2x}$

---

## Assignment 13: Advanced Factoring and General Solutions

### Part A
**Instruction:** Find an integral root by inspection, then factor by division.

**1.** $y^{(3)}+3y^{\prime\prime}-4y=0$

The characteristic equation is $P(r) = r^{3} + 3 r^{2} - 4 = 0$.
By inspection, $r = 1$ is an integral root.
Factoring the polynomial gives: $\left(r - 1\right) \left(r + 2\right)^{2} = 0$.
The roots are: $1, -2$.
**General Solution:** $y(x) = c_1  e^{1x} + c_2  e^{-2x} + c_3 x e^{-2x}$

---
**2.** $y^{(3)}-y^{\prime\prime}-5y^{\prime}-2y=0$

The characteristic equation is $P(r) = r^{3} - r^{2} - 5 r - 2 = 0$.
Factoring gives: $r^{3} - r^{2} - 5 r - 2 = 0$.
The roots are: $\frac{1}{3} + \frac{16}{9 \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}} + \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}, \frac{1}{3} + \frac{16}{9 \left(- \frac{1}{2} + \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}} + \left(- \frac{1}{2} + \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}, \frac{1}{3} + \left(- \frac{1}{2} - \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}} + \frac{16}{9 \left(- \frac{1}{2} - \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}}$.
**General Solution:** $y(x) = c_1  e^{\frac{16 \operatorname{re}{\left(\frac{1}{\left(- \frac{1}{2} + \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}}\right)}}{9} - \frac{2 \cos{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3} - \frac{2 \sqrt{3} \sin{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3} + \frac{1}{3}x} \cos(\frac{16 \operatorname{im}{\left(\frac{1}{\left(- \frac{1}{2} + \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}}\right)}}{9} - \frac{2 \sin{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3} + \frac{2 \sqrt{3} \cos{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3}x) + c_2  e^{\frac{16 \operatorname{re}{\left(\frac{1}{\left(- \frac{1}{2} + \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}}\right)}}{9} - \frac{2 \cos{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3} - \frac{2 \sqrt{3} \sin{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3} + \frac{1}{3}x} \sin(\frac{16 \operatorname{im}{\left(\frac{1}{\left(- \frac{1}{2} + \frac{\sqrt{3} i}{2}\right) \sqrt[3]{\frac{101}{54} + \frac{\sqrt{687} i}{18}}}\right)}}{9} - \frac{2 \sin{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3} + \frac{2 \sqrt{3} \cos{\left(\frac{\operatorname{atan}{\left(\frac{3 \sqrt{687}}{101} \right)}}{3} \right)}}{3}x)$

---
**3.** $y^{(3)}+27y=0$

The characteristic equation is $P(r) = r^{3} + 27 = 0$.
By inspection, $r = -3$ is an integral root.
Factoring the polynomial gives: $\left(r + 3\right) \left(r^{2} - 3 r + 9\right) = 0$.
The roots are: $-3, \frac{3}{2} - \frac{3 \sqrt{3} i}{2}, \frac{3}{2} + \frac{3 \sqrt{3} i}{2}$.
**General Solution:** $y(x) = c_1  e^{-3x} + c_2  e^{\frac{3}{2}x} \cos(\frac{3 \sqrt{3}}{2}x) + c_3  e^{\frac{3}{2}x} \sin(\frac{3 \sqrt{3}}{2}x)$

---
**4.** $y^{(4)}-y^{(3)}+y^{\prime\prime}-3y^{\prime}-6y=0$

The characteristic equation is $P(r) = r^{4} - r^{3} + r^{2} - 3 r - 6 = 0$.
By inspection, $r = 2$ is an integral root.
Factoring the polynomial gives: $\left(r - 2\right) \left(r + 1\right) \left(r^{2} + 3\right) = 0$.
The roots are: $2, -1, - \sqrt{3} i, \sqrt{3} i$.
**General Solution:** $y(x) = c_1  e^{2x} + c_2  e^{-1x} + c_3   \cos(\sqrt{3}x) + c_4   \sin(\sqrt{3}x)$

---
**5.** $y^{(3)}+3y^{\prime\prime}+4y^{\prime}-8y=0$

The characteristic equation is $P(r) = r^{3} + 3 r^{2} + 4 r - 8 = 0$.
By inspection, $r = 1$ is an integral root.
Factoring the polynomial gives: $\left(r - 1\right) \left(r^{2} + 4 r + 8\right) = 0$.
The roots are: $1, -2 - 2 i, -2 + 2 i$.
**General Solution:** $y(x) = c_1  e^{1x} + c_2  e^{-2x} \cos(2x) + c_3  e^{-2x} \sin(2x)$

---
**6.** $y^{(4)}+y^{(3)}-3y^{\prime\prime}-5y^{\prime}-2y=0$

The characteristic equation is $P(r) = r^{4} + r^{3} - 3 r^{2} - 5 r - 2 = 0$.
By inspection, $r = 2$ is an integral root.
Factoring the polynomial gives: $\left(r - 2\right) \left(r + 1\right)^{3} = 0$.
The roots are: $2, -1$.
**General Solution:** $y(x) = c_1  e^{2x} + c_2  e^{-1x} + c_3 x e^{-1x} + c_4 xx e^{-1x}$

---
### Part B
**Instruction:** Find the general solution given one solution.

**1.** $y^{(3)}+3y^{\prime\prime}-54y=0$ with $y=e^{3x}$
Since $r=3$ is a root of $r^3+3r^2-54=0$, we divide by $(r-3)$ to get $r^2+6r+18=0$, with roots $-3 \pm 3i$.
**General Solution:** $y(x) = c_1 e^{3x} + c_2 e^{-3x}\cos(3x) + c_3 e^{-3x}\sin(3x)$

---
**2.** $3y^{(3)}-2y^{\prime\prime}+12y^{\prime}-8y=0$ with $y=e^{2x/3}$
Root $r=2/3$, divide $(3r-2)$ into polynomial to get $r^2+4=0$, roots $\pm 2i$.
**General Solution:** $y(x) = c_1 e^{2x/3} + c_2 \cos(2x) + c_3 \sin(2x)$

---
**3.** $6y^{(4)}+5y^{(3)}+25y^{\prime\prime}+20y^{\prime}+4y=0$ with $y=\cos 2x$
Roots include $\pm 2i$. Divide polynomial by $(r^2+4)$ to get $6r^2+5r+1=0$, roots $-1/2, -1/3$.
**General Solution:** $y(x) = c_1 \cos(2x) + c_2 \sin(2x) + c_3 e^{-x/2} + c_4 e^{-x/3}$

---
**4.** $9y^{(3)}+11y^{\prime\prime}+4y^{\prime}-14y=0$ with $y=e^{-x}\sin x$
Roots include $-1 \pm i$. Divide polynomial by $(r^2+2r+2)$ to get $9r-7=0 \implies r=7/9$.
**General Solution:** $y(x) = c_1 e^{-x}\cos x + c_2 e^{-x}\sin x + c_3 e^{7x/9}$

---
**5.** Find $y(x)$ such that $y^{(4)}(x)=y(x)$, and $y(0)=18, y^{\prime}(0)=12, y^{\prime\prime}(0)=13, y^{(3)}(0)=7$.
Roots of $r^4-1=0$ are $\pm 1, \pm i$. General solution: $y = c_1 e^x + c_2 e^{-x} + c_3 \cos x + c_4 \sin x$.
Solving IVP with Sympy:
**Final Answer:** $y(x) = \frac{25 e^{x}}{2} + \frac{5 \sin{\left(x \right)}}{2} + \frac{5 \cos{\left(x \right)}}{2} + 3 e^{- x}$

---
**6.** Find a general solution of $y^{\prime\prime}-2iy^{\prime}+3y=0$.
Characteristic equation: $r^2 - 2ir + 3 = 0$. Using quadratic formula: $r = \frac{2i \pm \sqrt{-4 - 12}}{2} = i \pm 2i = 3i, -i$.
**Final Answer:** $y(x) = c_1 e^{3ix} + c_2 e^{-ix}$ (or equivalent combinations over $\mathbb{C}$)

---

## Assignment 15: Setting up Forms of Particular Solutions

**Instruction:** Set up the appropriate form of $y_p$ (do NOT solve for coefficients).

1. $y^{\prime\prime}-2y^{\prime}+2y=e^{x}\sin x$ 
Roots: $1 \pm i$. RHS root: $1 \pm i$ (multiplicity 1). 
**Form:** $y_p = x e^x (A \cos x + B \sin x)$

---
2. $y^{(5)}-y^{(3)}=e^{x}+2x^{2}-5$ 
Roots: $0,0,0,1,-1$. RHS roots: $1$ (mult 1), $0$ (mult 3 for $2x^2-5$). 
**Form:** $y_p = A x e^x + x^3 (B x^2 + C x + D)$

---
3. $y^{\prime\prime}+4y=3x\cos 2x$ 
Roots: $\pm 2i$. RHS root: $\pm 2i$ (multiplicity 1). 
**Form:** $y_p = x ((Ax+B)\cos 2x + (Cx+D)\sin 2x)$

---
4. $y^{(3)}+y^{\prime\prime}-12y^{\prime}=x-2xe^{-3x}$ 
Roots: $0, 3, -4$. RHS roots: $0$ (mult 2 for $x$), $-3$ (mult 2 for $xe^{-3x}$). 
**Form:** $y_p = x(Ax + B) + e^{-3x}(Cx+D)$

---
5. $y^{\prime\prime}+3y^{\prime}+2y=x(e^{x}-e^{-2x})$ 
Roots: $-1, -2$. RHS roots: $1$ (mult 2 for $xe^x$), $-2$ (mult 2 for $xe^{-2x}$). RHS root $-2$ matches. 
**Form:** $y_p = (Ax+B)e^x + x(Cx+D)e^{-2x}$

---
6. $y^{\prime\prime}-6y^{\prime}+13y=xe^{3x}\sin 2x$ 
Roots: $3\pm 2i$. RHS root: $3\pm 2i$ (mult 2 because of $x$). Matching means multiply by $x$. 
**Form:** $y_p = x e^{3x} ((Ax+B)\cos 2x + (Cx+D)\sin 2x)$

---
7. $y^{(4)}+5y^{\prime\prime}+4y=\sin x+\cos 2x$ 
Roots: $\pm i, \pm 2i$. RHS roots: $\pm i, \pm 2i$. 
**Form:** $y_p = x(A\cos x + B\sin x) + x(C\cos 2x + D\sin 2x)$

---
8. $y^{(4)}+9y^{\prime\prime}=(x^{2}+1)\sin 3x$ 
Roots: $0, 0, \pm 3i$. RHS root: $\pm 3i$ (mult 3). Matching multipy by $x$. 
**Form:** $y_p = x ((Ax^2+Bx+C)\cos 3x + (Dx^2+Ex+F)\sin 3x)$

---
9. $(D-\frac{1}{3})(D^{2}-4)y=xe^{x}+e^{2x}+e^{-2x}$ 
Roots: $1/3, 2, -2$. RHS roots: $1$ (mult 2), $2$ (mult 1), $-2$ (mult 1). 
**Form:** $y_p = (Ax+B)e^x + C x e^{2x} + D x e^{-2x}$

---
10. $y^{(4)}-2y^{\prime\prime}+y=x^{2}\cos x$ 
Roots: $1, 1, -1, -1$. RHS root: $\pm i$ (mult 3). No match. 
**Form:** $y_p = (Ax^2+Bx+C)\cos x + (Dx^2+Ex+F)\sin x$

---
