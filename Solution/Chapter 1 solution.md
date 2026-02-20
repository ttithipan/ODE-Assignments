# Solutions: Differential Equations Assignments 1-12

## Assignment 1

**1. The time rate of change of the velocity $v(t)$ of a coasting motorboat is proportional to the square of $v$.**
* **Derivation:** "Time rate of change of velocity" means the derivative of $v$ with respect to $t$, or $\frac{dv}{dt}$. "Proportional to" means we multiply by a constant $k$. "Square of $v$" is $v^2$.
* **Equation:** $\frac{dv}{dt} = k v^2$

**2. The acceleration $\frac{dv}{dt}$ of a Lamborghini is proportional to the difference between 250 km/h and the velocity of the car.**
* **Derivation:** The acceleration is given as $\frac{dv}{dt}$. The difference between 250 and velocity is $(250 - v)$. Proportionality gives a constant $k$.
* **Equation:** $\frac{dv}{dt} = k(250 - v)$

**3. In a city having a fixed population $P$, the rate of change of the number $N(t)$ of people who have heard a rumor is proportional to the number of people who have not yet heard it.**
* **Derivation:** The rate of change is $\frac{dN}{dt}$. The number of people who have not heard the rumor is the total population $P$ minus the number who have heard it $N$, yielding $(P - N)$.
* **Equation:** $\frac{dN}{dt} = k(P - N)$

**4. In a city with a fixed population $P$, the rate of change of the number $N(t)$ of people infected with a contagious disease is proportional to the product of the number of infected and uninfected individuals.**
* **Derivation:** The rate of change is $\frac{dN}{dt}$. The number of infected is $N$, and uninfected is $(P - N)$. The product is $N(P - N)$.
* **Equation:** $\frac{dN}{dt} = k N(P - N)$


## Assignment 2

**1. Show that the general solution of $\frac{dx}{dt}=kx^{2}$ is $x(t)=\frac{1}{(C-k)t}$ (Wait, the question says $\frac{1}{(C-k)t}$... wait, let's verify: $\frac{dx}{dt} = kx^2 \implies \int x^{-2}dx = \int k dt \implies -x^{-1} = kt + C_1 \implies x = \frac{-1}{kt + C_1}$. If $x(t) = \frac{1}{(C-k)t}$, then $x' = \frac{-(C-k)}{((C-k)t)^2} = \frac{-(C-k)}{(C-k)^2 t^2} = \frac{-1}{(C-k)t^2}$. Let's see: $kx^2 = \frac{k}{(C-k)^2 t^2}$. This does not match unless $-(C-k) = k \implies -C+k=k \implies C=0$. The question in the text says $x(t)=\frac{1}{C-kt}$. Let's assume the question meant $\frac{1}{C-kt}$.) Determine by inspection a solution of the IVP $\frac{dx}{dt}=kx^{2}, x(0)=0$.**
* **Derivation & Method:** 
  Separation of variables: $\frac{dx}{x^2} = k dt$. Integrating both sides gives $-\frac{1}{x} = kt - C \implies \frac{1}{x} = C - kt \implies x(t) = \frac{1}{C - kt}$. 
  For the IVP $x(0) = 0$, if we use $x(t) = \frac{1}{C-kt}$, $x(0) = 1/C \neq 0$ for any finite $C$. However, by inspection, the trivial solution $x(t) = 0$ satisfies both the differential equation ($\frac{d}{dt}(0) = k(0)^2 = 0$) and the initial condition.
* **Solution:** General solution verified as $x(t) = \frac{1}{C-kt}$. The solution to the IVP by inspection is $x(t) = 0$.

**2. A rodent population $P(t)$ satisfies $\frac{dP}{dt}=kP^{2}$. Initially, $P(0)=2$. When $P=10$, the rate is $\frac{dP}{dt}=1$. Determine $k$, compute time to 100 and 1000 rodents. Interpret result.**
* **Derivation & Method:**
  From $\frac{dP}{dt} = kP^2$, when $P=10$, $\frac{dP}{dt} = 1$. Substitute these in: $1 = k(10)^2 \implies k = \frac{1}{100} = 0.01$.
  The general solution for $\frac{dP}{dt} = kP^2$ is $P(t) = \frac{1}{C - kt}$ (as derived in question 1).
  Apply initial condition $P(0) = 2 \implies 2 = \frac{1}{C - 0} \implies C = 0.5$.
  So, $P(t) = \frac{1}{0.5 - 0.01t}$.
  Time to reach $P=100$: $100 = \frac{1}{0.5 - 0.01t} \implies 0.5 - 0.01t = 0.01 \implies 0.01t = 0.49 \implies t = 49$.
  Time to reach $P=1000$: $1000 = \frac{1}{0.5 - 0.01t} \implies 0.5 - 0.01t = 0.001 \implies 0.01t = 0.499 \implies t = 49.9$.
  Interpretation: As $t \to 50$ from below, the denominator $0.5 - 0.01t \to 0$, meaning $P(t) \to \infty$. This represents finite-time blowup (doomsday scenario). 
* **Final answers:** $k = 0.01$. Time to 100 is $t=49$. Time to 1000 is $t=49.9$. The population blows up to infinity as $t \to 50$.

**3. The velocity $v(t)$ of a coasting motorboat satisfies $\frac{dv}{dt}=-kv^{2}$. Given $v(0)=10\text{ m/s}$ and $\frac{dv}{dt}=-1$ when $v=5\text{ m/s}$. Find $k$, time for $v$ to reach 1 m/s and 0.1 m/s. What happens as $t \to \infty$? When does the boat stop?**
* **Derivation & Method:**
  Substitute points into DE: $-1 = -k(5)^2 \implies k = \frac{1}{25} = 0.04$.
  Solve DE by separation of variables: $\int v^{-2} dv = \int -0.04 dt \implies -v^{-1} = -0.04t - C \implies \frac{1}{v} = 0.04t + C \implies v(t) = \frac{1}{0.04t + C}$.
  Using $v(0) = 10 \implies 10 = \frac{1}{C} \implies C = 0.1$.
  So $v(t) = \frac{1}{0.04t + 0.1} = \frac{25}{t + 2.5}$.
  Time to $v = 1\text{ m/s}$: $1 = \frac{25}{t + 2.5} \implies t + 2.5 = 25 \implies t = 22.5\text{ s}$.
  Time to $v = 0.1\text{ m/s}$: $0.1 = \frac{25}{t + 2.5} \implies t + 2.5 = 250 \implies t = 247.5\text{ s}$.
  As $t \to \infty$: $v(t) \to 0$. The velocity approaches zero asymptotically but never actually mathematical reaches 0 for any finite $t$. So theoretically, it "stops" at $t = \infty$.
* **Final answers:** $k=0.04$. $v=1$ at $t=22.5\text{ s}$. $v=0.1$ at $t=247.5\text{ s}$. Velocity goes to 0 as $t \to \infty$. The boat theoretically never stops in finite time.


### Part B
**Find explicit particular solutions of the following initial value problems:**

**1. $\frac{dy}{dx}=ye^{x}$, (0)=2e$**
* $\frac{dy}{y} = e^x dx \implies \ln|y| = e^x + C$.
* (0) = 2e \implies \ln(2e) = e^0 + C \implies \ln 2 + 1 = 1 + C \implies C = \ln 2$.
* $\ln y = e^x + \ln 2 \implies y = e^{e^x + \ln 2} = e^{\ln 2} e^{e^x} = 2e^{e^x}$.

**2. $\frac{dy}{dx}=3x^{2}(y^{2}+1)$, (0)=1$**
* $\frac{dy}{y^2+1} = 3x^2 dx \implies \arctan y = x^3 + C$.
* (0) = 1 \implies \arctan 1 = 0 + C \implies C = \frac{\pi}{4}$.
* $\arctan y = x^3 + \frac{\pi}{4} \implies y = \tan(x^3 + \frac{\pi}{4})$.

**3. \frac{dy}{dx}=\frac{x}{\sqrt{x^{2}-16}}$, (5)=2$**
*  dy = (x^2-16)^{-1/2} x dx \implies y^2 = (x^2-16)^{1/2} + C = \sqrt{x^2-16} + C$.
* (5) = 2 \implies 4 = \sqrt{25-16} + C = 3 + C \implies C = 1$.
* ^2 = \sqrt{x^2-16} + 1$. Since (5)=2 > 0$, take the positive root:  = \sqrt{\sqrt{x^2-16} + 1}$.

**4. $\frac{dy}{dx}=4x^{3}y-y$, (1)=-3$**
* $\frac{dy}{dx} = y(4x^3 - 1) \implies \frac{dy}{y} = (4x^3 - 1) dx \implies \ln|y| = x^4 - x + C$.
* (1) = -3 \implies \ln|-3| = 1 - 1 + C \implies C = \ln 3$.
* $|y| = e^{x^4 - x + \ln 3} = 3e^{x^4 - x}$. Since (1) = -3$, the solution is negative:  = -3e^{x^4 - x}$.

**5. $\frac{dy}{dx}+1=2y$, (1)=1$**
* $\frac{dy}{dx} = 2y - 1 \implies \frac{dy}{2y-1} = dx \implies \frac{1}{2}\ln|2y-1| = x + C$.
* (1) = 1 \implies \frac{1}{2}\ln|2(1)-1| = 1 + C \implies \frac{1}{2}\ln 1 = 1 + C \implies C = -1$.
* $\ln(2y-1) = 2x - 2 \implies 2y - 1 = e^{2x-2} \implies y = \frac{1}{2}(e^{2x-2} + 1)$.

**6. $\frac{dy}{dx}=y\cot x$, (\frac{1}{2}\pi)=\frac{1}{2}\pi$**
* $\frac{dy}{y} = \cot x dx \implies \ln|y| = \ln|\sin x| + C$.
* (\frac{\pi}{2}) = \frac{\pi}{2} \implies \ln(\frac{\pi}{2}) = \ln(1) + C \implies C = \ln(\frac{\pi}{2})$.
* $\ln y = \ln(\sin x) + \ln(\frac{\pi}{2}) = \ln(\frac{\pi}{2}\sin x) \implies y = \frac{\pi}{2}\sin x$.

**7. \frac{dy}{dx}-y=2x^{2}y$, (1)=1$**
* \frac{dy}{dx} = y + 2x^2y = y(1 + 2x^2) \implies \frac{dy}{y} = (\frac{1}{x} + 2x) dx$.
* $\ln|y| = \ln|x| + x^2 + C$.
* (1) = 1 \implies \ln 1 = \ln 1 + 1 + C \implies C = -1$.
* $\ln y = \ln x + x^2 - 1 \implies y = e^{\ln x + x^2 - 1} = x e^{x^2 - 1}$.

**8. $\frac{dy}{dx}=2xy^{2}+3x^{2}y^{2}$, (1)=-1$**
* $\frac{dy}{dx} = y^2(2x + 3x^2) \implies y^{-2} dy = (2x + 3x^2) dx$.
* $-y^{-1} = x^2 + x^3 + C \implies -\frac{1}{y} = x^2 + x^3 + C$.
* (1) = -1 \implies 1 = 1 + 1 + C \implies C = -1$.
* $-\frac{1}{y} = x^2 + x^3 - 1 \implies y = \frac{1}{1 - x^2 - x^3}$.

**9. $\frac{dy}{dx}=6e^{2xy}$, (0)=0$**
*(Note: As written, ^{2xy}$ is not separable. This is almost certain a typographical error for ^{2x-y}$ or ^{2x+y}$. We will solve assuming the standard typo $\frac{dy}{dx} = 6e^{2x-y}$.)*
* $\frac{dy}{dx} = 6e^{2x}e^{-y} \implies e^y dy = 6e^{2x} dx$.
* ^y = 3e^{2x} + C$.
* (0) = 0 \implies e^0 = 3e^0 + C \implies 1 = 3 + C \implies C = -2$.
* ^y = 3e^{2x} - 2 \implies y = \ln(3e^{2x} - 2)$.

**10. \sqrt{x}\frac{dy}{dx}=\cos^{2}y$, (4)=\frac{\pi}{4}$**
* $\frac{dy}{\cos^2 y} = \frac{dx}{2\sqrt{x}} \implies \sec^2 y dy = \frac{1}{2}x^{-1/2} dx$.
* $\tan y = \sqrt{x} + C$.
* (4) = \frac{\pi}{4} \implies \tan(\frac{\pi}{4}) = \sqrt{4} + C \implies 1 = 2 + C \implies C = -1$.
* $\tan y = \sqrt{x} - 1 \implies y = \arctan(\sqrt{x} - 1)$.
