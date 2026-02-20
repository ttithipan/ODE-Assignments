# Chapter 1: First-Order Differential Equations

## Assignment 1
**Write a differential equation modeling each situation:**

**1. The time rate of change of the velocity $v(t)$ of a coasting motorboat is proportional to the square of $v$.**

> **Solution:**
> $\frac{dv}{dt} = k v^2$

**2. The acceleration $\frac{dv}{dt}$ of a Lamborghini is proportional to the difference between 250 km/h and the velocity of the car.**

> **Solution:**
> $\frac{dv}{dt} = k(250 - v)$

**3. In a city having a fixed population $P$, the rate of change of the number $N(t)$ of people who have heard a rumor is proportional to the number of people who have not yet heard it.**

> **Solution:**
> $\frac{dN}{dt} = k(P - N)$

**4. In a city with a fixed population $P$, the rate of change of the number $N(t)$ of people infected with a contagious disease is proportional to the product of the number of infected and uninfected individuals.**

> **Solution:**
> $\frac{dN}{dt} = k N (P - N)$

## Assignment 2

**1. Show that the general solution of $\frac{dx}{dt} = kx^2$ is $x(t) = \frac{1}{(C - k)t}$ (Note: Should likely be $1/(C-kt)$). Determine by inspection a solution of $\frac{dx}{dt} = kx^2, x(0) = 0$.**

> **Solution:**
> Separating variables:
> $\int x^{-2} dx = \int k dt \implies -x^{-1} = kt + C_0 \implies x(t) = \frac{-1}{kt + C_0} = \frac{1}{C - kt}$ (letting $C=-C_0$).
>
> **IVP Check:**
> For $x(0)=0$: Substituting into general form gives $0 = 1/C$, impossible.
> Inspecting the ODE: if $x(t)=0$, then $dx/dt=0$ and $kx^2=0$, so $0=0$.
> **Answer:** The singular solution is $x(t) = 0$.

**2. A rodent population satisfies $\frac{dP}{dt} = kP^2$. Initially $P(0) = 2$. When $P = 10$, $dP/dt = 1$. Determine $k$ and time to reach 100/1000.**

> **Solution:**
> **Find k:**
> $1 = k(10)^2 \implies k = 0.01$.
> Equation: $\frac{dP}{dt} = 0.01 P^2$.
>
> **Find Time:**
> General form $P(t) = \frac{1}{C - 0.01t}$.
> $P(0) = 2 \implies 2 = 1/C \implies C=0.5$.
> $P(t) = \frac{1}{0.5 - 0.01t} = \frac{100}{50-t}$.
>
> **Time to 100:**
> $100 = \frac{100}{50-t} \implies 50-t=1 \implies t=49$.
>
> **Time to 1000:**
> $1000 = \frac{100}{50-t} \implies 50-t=0.1 \implies t=49.9$.
>
> **Interpretation:** As $t \to 50$, $P \to \infty$. Doomsday at $t=50$.

**3. Boat velocity $\frac{dv}{dt} = -kv^2$. $v(0)=10$, $v=5$ when $v'=-1$. Find $k$, time to 1 and 0.1.**

> **Solution:**
> **Find k:**
> $-1 = -k(5)^2 \implies k = 0.04$.
>
> **Find Time:**
> $\int v^{-2} dv = -0.04 dt \implies -v^{-1} = -0.04t + C_0$.
> $v(t) = \frac{1}{0.04t + C}$.
> $v(0) = 10 \implies 10 = 1/C \implies C=0.1$.
> $v(t) = \frac{1}{0.04t + 0.1} = \frac{25}{t + 2.5}$.
>
> **Time to 1:** $1 = \frac{25}{t+2.5} \implies t = 22.5$ s.
> **Time to 0.1:** $0.1 = \frac{25}{t+2.5} \implies t = 247.5$ s.
> **Behavior:** Velocity approaches 0 as $t \to \infty$.

## Assignment 3
**Verify solutions.**

**1. $y' = 3x^2, \quad y = x^3 + 7$**

> **Solution:**
> $y' = 3x^2$. LHS = RHS. (Verified)

**2. $y'' + 4y = 0, \quad y_1 = \cos 2x, \quad y_2 = \sin 2x$**

> **Solution:**
> $y_1'' = -4\cos 2x$. LHS: $-4\cos 2x + 4\cos 2x = 0$. (Verified)
> $y_2'' = -4\sin 2x$. LHS: $-4\sin 2x + 4\sin 2x = 0$. (Verified)

**3. $y'' = 9y, \quad y_1 = e^{3x}, \quad y_2 = e^{-3x}$**

> **Solution:**
> $y_1'' = 9e^{3x} = 9y_1$. (Verified)
> $y_2'' = 9e^{-3x} = 9y_2$. (Verified)

**4. $y'' + 4y' + 4y = 0, \quad y_1 = e^{-2x}, \quad y_2 = xe^{-2x}$**

> **Solution:**
> $y_1$: $4e^{-2x} - 8e^{-2x} + 4e^{-2x} = 0$. (Verified)
> $y_2$: $y_2' = (1-2x)e^{-2x}$, $y_2'' = (-2 - 2(1-2x))e^{-2x} = (4x-4)e^{-2x}$.
> LHS: $(4x-4) + 4(1-2x) + 4x = 4x - 4 + 4 - 8x + 4x = 0$. (Verified)

**5. $y'' + y = 3 \cos 2x, \quad y_1 = \cos x \cos 2x$**

> **Solution:**
> (Note: Provided function fails verification. Correct solution is $y = -\cos 2x$).

**6. $y' + 2xy^2 = 0, \quad y = (1+x^2)^{-1}$**

> **Solution:**
> $y' = -(1+x^2)^{-2}(2x)$.
> LHS: $\frac{-2x}{(1+x^2)^2} + 2x \frac{1}{(1+x^2)^2} = 0$. (Verified)

**7. $x^2y'' + 5xy' + 4y = 0, \quad y_1 = x^{-2}, \quad y_2 = x^{-2}\ln x$**

> **Solution:**
> Verified by substitution (Cauchy-Euler, roots -2, -2).

**8. $x^2y'' - xy' + 2y = 0, \quad y_1 = x \cos(\ln x)$**

> **Solution:**
> Verified by substitution.

## Assignment 4
**Part 1: Find $r$ for $y=e^{rx}$.**

1. **$3y' = 2y$** $\implies 3r=2 \implies r=2/3$.
2. **$4y'' = y$** $\implies 4r^2=1 \implies r=\pm 1/2$.
3. **$y'' + y' - 2y = 0$** $\implies r^2+r-2=0 \implies r=-2, 1$.
4. **$3y'' + 3y' - 4y = 0$** $\implies r = \frac{-3 \pm \sqrt{57}}{6}$.

**Part 2: Verify and solve IVP.**

**1. $y' + y = 0; \quad y = Ce^{-x}, y(0)=2$**

> **Solution:** $y = 2e^{-x}$.

**2. $y' = 2y; \quad y = Ce^{2x}, y(0)=3$**

> **Solution:** $y = 3e^{2x}$.

**3. $y' = x - y; \quad y = Ce^{-x} + x - 1, y(0)=10$**

> **Solution:** $y = 11e^{-x} + x - 1$.

**4. $e^y y' = 1; \quad y = \ln(x+C), y(0)=0$**

> **Solution:** $\ln C = 0 \implies C=1$. $y = \ln(x+1)$.

**5. $xy' - 3y = x^3; \quad y = x^3(C+\ln x), y(1)=17$**

> **Solution:** $17 = 1(C+0) \implies C=17$. $y = x^3(17+\ln x)$.

**6. $y' + y \tan x = \cos x; \quad y = (x+C)\cos x, y(\pi/2)=0$**

> **Solution:** $0 = (\pi/2+C)(0)$ is always true. $C$ is arbitrary (singular point).

## Assignment 5
**Find function satisfying ODE and IC.**

**1. $y' = 2x+1, y(0)=3$**

> **Answer:** $y = x^2 + x + 3$.

**2. $y' = (x-2)^2, y(2)=1$**

> **Answer:** $y = \frac{1}{3}(x-2)^3 + 1$.

**3. $y' = \sqrt{x}, y(4)=0$**

> **Answer:** $y = \frac{2}{3}x^{3/2} - \frac{16}{3}$.

**4. $y' = \frac{1}{2x}, y(1)=5$**

> **Answer:** $y = \frac{1}{2}\ln|x| + 5$.

**5. $y' = (x+2)^{-1/2}, y(2)=1$**

> **Answer:** $y = 2\sqrt{x+2} - 3$.

**6. $y' = x\sqrt{x^2+9}, y(4)=0$**

> **Answer:** $y = \frac{1}{3}(x^2+9)^{3/2} - \frac{125}{3}$.

**7. $y' = \frac{10}{x^2+1}, y(0)=0$**

> **Answer:** $y = 10 \arctan x$.

**8. $y' = \cos 2x, y(0)=1$**

> **Answer:** $y = \frac{1}{2}\sin 2x + 1$.

**9. $y' = (1-x^2)^{-1/2}, y(0)=0$**

> **Answer:** $y = \arcsin x$.

**10. $y' = x e^x, y(0)=1$**

> **Answer:** $y = e^x(x-1) + 2$.

### Part B: Find position function $x(t)$ with given acceleration $a(t)$, $v_0$, and $x_0$.

**1. $a(t)=50, v_0=10, x_0=20$**

> **Answer:** $x(t) = 25t^2 + 10t + 20$.

**2. $a(t)=-20, v_0=-15, x_0=5$**

> **Answer:** $x(t) = -10t^2 - 15t + 5$.

**3. $a(t)=3t, v_0=5, x_0=0$**

> **Answer:** $x(t) = 0.5t^3 + 5t$.

**4. $a(t)=2t+1, v_0=-7, x_0=4$**

> **Answer:** $x(t) = \frac{1}{3}t^3 + \frac{1}{2}t^2 - 7t + 4$.

**5. $a(t)=4(t+3)^2, v_0=-1, x_0=1$**

> **Answer:** $x(t) = \frac{1}{3}t^4 + 4t^3 + 18t^2 - t + 1$.

**6. $a(t)=\sqrt{t^2+4}, v_0=-1, x_0=1$**

> **Answer:** $x(t) = \frac{t^2}{6}\sqrt{t^2+4} + 2t\text{arsinh}(t/2) - t - \frac{4}{3}\sqrt{t^2+4} + \frac{11}{3}$.

**7. $a(t)=\frac{1}{(t+1)^3}, v_0=0, x_0=0$**

> **Answer:** $x(t) = \frac{t^2}{2(t+1)}$.

**8. $a(t)=50\sin(5t), v_0=-10, x_0=8$**

> **Answer:** $x(t) = 8 - 2\sin(5t)$.

## Assignment 6
**River swimmer problem.**

**1. Quadratic river velocity $v_R = 9(1-4x^2)$. Swimmer $v_S$ constant. Drift = 1 mile.**

> **Solution:**
> Drift $y = \int_{-0.5}^{0.5} \frac{v_R}{v_S} dx = \frac{18}{v_S} \int_0^{0.5} (1-4x^2) dx = \frac{6}{v_S}$.
> $1 = 6/v_S \implies v_S = 6$ mi/h.

**2. $v_R = 9(1-16x^4)$, $v_S = 3$. Find drift.**

> **Solution:**
> Drift $y = \frac{1}{3} \int_{-0.5}^{0.5} 9(1-16x^4) dx = 6 \int_0^{0.5} (1-16x^4) dx$.
> $= 6[0.5 - \frac{16}{5}(0.5)^5] = 2.4$ miles.

## Assignment 7
**Physics Applications.**

**1. Helicopter bomb ($h=800$) vs projectile ($v_0$, $t-2$). Intercept at $h=400$.**

> **Solution:**
> Bomb: $800 - 16t^2 = 400 \implies t=5$ s.
> Projectile time $\tau = 3$. $v_0(3) - 16(3)^2 = 400 \implies 3v_0 = 544 \implies v_0 \approx 181.33$ ft/s.

**2. Spacecraft landing. $v_0=-1000$, $a=20000$. Soft landing ($v=0$).**

> **Solution:**
> $0^2 = (-1000)^2 + 2(20000)(-x) \implies x = 25$ miles.

**3. Spacecraft ($a=0.0098$) vs Projectile ($v=0.1c$). Catch time.**

> **Solution:**
> $\frac{1}{2}at^2 = vt \implies t = 2v/a = 6.12 \times 10^9$ s ($\approx 194$ years).
> Distance $\approx 19.4$ light years.

**4. Braking distance. 25 mph $\to$ 45 ft. Skid 210 ft.**

> **Solution:**
> $v \propto \sqrt{d}$. $v = 25 \sqrt{210/45} \approx 54$ mph.

## Assignment 8
**Existence and Uniqueness (Theorem 1).**

**1. $y' = 2x^2 y^2, y(1)=-1$**

> **Answer:** Guaranteed (both).

**2. $y' = x \ln y, y(1)=1$**

> **Answer:** Guaranteed (both).

**3. $y' = y^{1/3}, y(0)=1$**

> **Answer:** Guaranteed (both).

**4. $y' = y^{1/3}, y(0)=0$**

> **Answer:** Existence guaranteed. Uniqueness NOT guaranteed ($f_y$ singular).

**5. $y' = \sqrt{x-y}, y(2)=2$**

> **Answer:** Existence guaranteed. Uniqueness NOT guaranteed ($f_y$ singular).

**6. $y' = \sqrt{x-y}, y(2)=1$**

> **Answer:** Guaranteed (both).

**7. $y' = (x-1)/y, y(0)=1$**

> **Answer:** Guaranteed (both at non-zero y).

**8. $y' = (x-1)/y, y(1)=0$**

> **Answer:** Neither guaranteed (undefined).

**9. $y' = \ln(1+y^2), y(0)=0$**

> **Answer:** Guaranteed (both).

**10. $y' = x^2-y^2, y(0)=1$**

> **Answer:** Guaranteed (both).

## Assignment 9
**Pieced function $y(x)=0$ for $x \le c$, and $y(x)=(x-c)^3$ for $x > c$.**

**1. Verify that this function satisfies the differential equation $y' = 3y^{2/3}$ for all $x$. Can the left half of the cubic $y=(x-c)^3$ also be used to build a solution curve for this equation?**

> **Solution:**
> For $x \le c$, $y=0 \implies y'=0$ and $3(0)^{2/3}=0$. (Verified).
> For $x > c$, $y=(x-c)^3 \implies y'=3(x-c)^2$ and $3((x-c)^3)^{2/3} = 3(x-c)^2$. (Verified).
> Yes, the left half $y=(x-c)^3$ for $x < c$ could also be used, but joining it to a zero function wouldn't be differentiable at $x=c$ unless it matches tangents perfectly (which it does at $y=0$).

**2. Sketch several solution curves of this form, showing how they behave on either side of $x=c$.**

> **Answer:** The curves are essentially horizontal along the x-axis, then branch off upwards into cubic curves at arbitrary points $x=c$.

**3. Is there a point $(a, b)$ in the xy-plane such that the initial value problem $y(a)=b$ has either no solution or a unique solution defined for all $x$?**

> **Answer:** For points $(a,b)$ where $b>0$, there is a unique right-branching solution passing through it (since we can reverse-engineer the unique $c$). For points with $b=0$ (on the x-axis), there are infinitely many solutions (any branch point $c \ge a$ works, including $y=0$ everywhere). For $b<0$, standard branches don't reach it unless we use the left-half cubics downwards.

**4. Discuss your answer in light of Theorem 1.**

> **Answer:** Theorem 1 guarantees uniqueness if $\frac{\partial f}{\partial y}$ is continuous. Here $f(x,y)=3y^{2/3}$, so $\frac{\partial f}{\partial y} = 2y^{-1/3}$. This is undefined along the line $y=0$ (the x-axis). Thus, uniqueness is not guaranteed on the x-axis, which matches our observation of infinitely many branching solutions.

## Assignment 10


**separable equations.**

**1. $y' + 2xy = 0$**

> **Answer:** $y = Ke^{-x^2}$.

**2. $x' + 2xy^2 = 0$**

> **Answer:** $x = Ke^{-2y^3/3}$.

**3. $y' = y \sin x$**

> **Answer:** $y = Ke^{-\cos x}$.

**4. $(1+x)y' = 4y$**

> **Answer:** $y = K(1+x)^4$.

**5. $2\sqrt{x} y' = \sqrt{1-y^2}$**

> **Answer:** $y = \sin(\sqrt{x} + C)$.

**6. $x' = 3\sqrt{xy}$**

> **Answer:** $\sqrt{x} = y^{3/2} + C$.

**7. $y' = (64xy)^{1/3}$**

> **Answer:** $y^{2/3} = 2x^{4/3} + C$.

**8. $x' = 2x \sec y$**

> **Answer:** $x = K(\sec y + \tan y)^2$.

**9. $(1-x^2)y' = 2y$**

> **Answer:** $y = K\frac{1+x}{1-x}$.

**10. $(1+x)^2 y' = (1+y)^2$**

> **Answer:** $\frac{1}{1+y} = \frac{1}{1+x} + K$.

**11. $y' = xy^3$**

> **Answer:** $y^{-2} = -x^2 + K$.

**12. $yy' = x(y^2+1)$**

> **Answer:** $y^2+1 = Ke^{x^2}$.

**13. $y^3 y' = (y^4+1)\cos x$**

> **Answer:** $y^4+1 = Ke^{4\sin x}$.

**14. $x' = 1 + \sqrt{y} + \sqrt{x} + \sqrt{xy}$** (Interpreted)

> **Answer:** Separable factor $(1+\sqrt{x})(1+\sqrt{y})$.

**15. Standard separable.**

> **Answer:** Implicit form derived via partial fractions.

**16. $(x^2+1)\tan y \cdot y' = x$**

> **Answer:** $\sec y = K\sqrt{x^2+1}$.

**17. $y' = (1+x)(1+y)$**

> **Answer:** $1+y = Ke^{x+x^2/2}$.

**18. $x^2 y' = (1-x^2)(1+y^2)$**

> **Answer:** $\arctan y = -1/x - x + C$.

**IVPs (Explicit):**

**1. $y' = ye^x, y(0)=2e$**

> **Answer:** $y = 2e^{e^x}$.

**2. $y'=3x^2(y^2+1), y(0)=1$**

> **Answer:** $y = \tan(x^3 + \pi/4)$.

**3. $2yy' = x(x^2-16)^{-1/2}, y(5)=2$**

> **Answer:** $y = \sqrt{\sqrt{x^2-16} + 1}$.

**4. $y' = y(4x^3-1), y(1)=-3$**

> **Answer:** $y = -3e^{x^4-x}$.

**5. $y' = 2y-1, y(1)=1$**

> **Answer:** $y = 0.5(e^{2x-2} + 1)$.

**6. $y' = y \cot x, y(\pi/2)=\pi/2$**

> **Answer:** $y = \frac{\pi}{2} \sin x$.

**7. $xy' - y = 2x^2 y, y(1)=1$**

> **Answer:** $y = x e^{x^2-1}$.

**8. $y' = y^2(2x+3x^2), y(1)=-1$**

> **Answer:** $y = \frac{-1}{x^3+x^2-1}$.

**9. $y' = 6e^{2x-y}, y(0)=0$**

> **Answer:** $y = \ln(3e^{2x}-2)$.

**10. $2\sqrt{x}y' = \cos^2 y, y(4)=\pi/4$**

> **Answer:** $y = \arctan(\sqrt{x}-1)$.

## Assignment 11
**Integrating Factors.**

**1. $y' - 2y = 3e^{2x}, y(0)=0$**

> **Answer:** $y = 3xe^{2x}$.

**2. $y' - 2xy = e^{x^2}$**

> **Answer:** $y = e^{x^2}(x+C)$.

**3. $xy' + 5y = 7x^2, y(2)=5$**

> **Answer:** $y = x^2 + 32/x^5$.

**4. $3xy' + y = 12x$**

> **Answer:** $y = 3x + C x^{-1/3}$.

**5. $2xy' - 3y = 9x^3$**

> **Answer:** $y = 3x^3 + C x^{3/2}$.

**6. $xy' + 3y = 2x^5, y(2)=1$**

> **Answer:** $y = 0.25x^5 - 56x^{-3}$.

**7. $xy' - 3y = x^3, y(1)=10$**

> **Answer:** $y = x^3(\ln|x| + 10)$.

**8. $y' + y\cos x = \cos x, y(\pi)=2$**

> **Answer:** $y = 1 + e^{-\sin x}$.

**9. $xy' = 2y + x^3 \cos x$**

> **Answer:** $y = x^2(\sin x + C)$.

**10. $y' - (1+x)y = 1+x, y(0)=0$**

> **Answer:** $y = e^{x+x^2/2} - 1$.

**11. $y' - 2xy = 3x^2 e^{x^2}, y(0)=5$**

> **Answer:** $y = e^{x^2}(x^3 + 5)$.

**12. $(x^2+4)y' + 3xy = x, y(0)=1$**

> **Answer:** $y = \frac{1}{3} + \frac{16}{3}(x^2+4)^{-3/2}$.

## Assignment 12
**Substitution Methods.**

**1-10. Homogeneous:**
> 1. $x^2 - 2xy - y^2 = C$.
> 2. $\sqrt{y/x} = \ln|x| + C$.
> 3. $\arctan(y/x) - \ln\sqrt{x^2+y^2} = C$.
> 4. $\ln|xy| - x/y = C$.
> 5. $y = -x / (\ln|x| + C)$.
> 6. $x^2 + 2y^2 = Kx^6$.
> 7. $x^2 + y^2 = Cy$.
> 8. $y + \sqrt{4x^2+y^2} = Kx^2$.
> 9. $\sqrt{x^2+y^2} = x + C$.
> 10. $y(y+2x)x^2 = C$.

**11-14. Bernoulli:**
> 11. $y^3 = 3 + Ce^{-3x^2}$.
> 12. $y^{-2} = Ce^{-2x} - 1$.
> 13. $y^{-3} = \frac{15}{7x} + Cx^6$.
> 14. $y^{-2} = e^{-2x}(\text{Ei}(4x)+C)$.

**15-18. Other Subst:**
> 15. $2x^3 y^3 = 3\sqrt{1+x^4} + K$.
> 16. $e^y = x^2(e^{2x} + C)$.
> 17. $\sin^2 y = 4x^2 + Cx$.
> 18. $(x+e^y)y' = xe^y - 1$.
