# Roots — Computational Methods Portfolio

This repository contains a collection of numerical analysis projects focused on **root-finding algorithms** and their applications to physics and mathematics problems.
Each exercise explores different iterative methods such as **Newton-Raphson**, **Halley’s Method**, **Secant Method**, **Fixed-Point Iteration**, and more.
The projects were developed using Python as part of the **Computational Methods** course.

---

## 📜 Projects

1.  [Halley’s Method — Root Convergence](#1-halleys-method--root-convergence)
2.  [Electric Force of a Charged Ring](#2-electric-force-of-a-charged-ring)
3.  [Kepler’s Equation — Halley’s Comet](#3-keplers-equation--halleys-comet)
4.  [Fraunhofer Diffraction by a Slit](#4-fraunhofer-diffraction-by-a-slit)
5.  [Lagrange Point ($\text{L}_1$) — Earth-Moon System](#5-lagrange-point-l_1--earth-moon-system)
6.  [**Planetary Radius Calculation (Gliese 832c)**](#6-planetary-radius-calculation-gliese-832c)
7.  [**Complex Transcendental Equation Solver**](#7-complex-transcendental-equation-solver)

---

### 1. Halley’s Method — Root Convergence

Implementation of **Halley’s Method**, which uses both first and second derivatives to achieve **cubic convergence**.
* Finds the first positive root of the function: $f(x) = \sin(x) + \cos(1 + x^2) - 1$
* Examines how convergence depends on the **tolerance** value.

### 2. Electric Force of a Charged Ring

Simulation of the **electric force** exerted by a uniformly charged ring on a point charge.
* Computes the force: $F = \frac{1}{4\pi\epsilon_0}\frac{qQx}{(x^2 + a^2)^{3/2}}$
* Uses the **Newton-Raphson** and **Fixed-Point** methods to find $x$ where $F = 1.25\,\text{N}$.
* Studies how the ring’s radius affects the resulting force.

### 3. Kepler’s Equation — Halley’s Comet

Numerical solution of **Kepler’s Equation** to find the **eccentric anomaly** ($E$): $M = E - e\sin(E)$
* Applies the **Bisection**, **Newton**, and **Secant** methods.
* Analyzes the orbit of **Halley’s Comet** using its real orbital parameters.
* Plots $E(t)$ for a full orbital period.

### 4. Fraunhofer Diffraction by a Slit

Computation and visualization of the **diffraction intensity pattern**: $I(\theta) = I_0 \left[\frac{\sin(\pi W \sin\theta / \lambda)}{\pi W \sin\theta / \lambda}\right]^2$
* Calculates and plots both $I(x)$ and $I'(x)$.
* Uses **Secant** and **Regula Falsi** methods to find the half-intensity points and maxima.

### 5. Lagrange Point ($\text{L}_1$) — Earth-Moon System

Numerical computation of the **Lagrange point ($\text{L}_1$)** between the Earth and the Moon: $\frac{GM}{r^2} - \frac{Gm}{(R - r)^2} = \omega^2 r$
* Solved using **Newton’s Method** and **Secant Method**.
* Determines the equilibrium distance ($r$) where gravitational and centrifugal forces balance.
* Uses physical parameters for the Earth-Moon system.

### 6. Planetary Radius Calculation (Gliese 832c) (NEW)

Numerical determination of the radius ($R$) of the exoplanet Gliese 832c ($M=5.40 M_{\oplus}$) by solving the mass equation $M(R) = M_{\text{g832c}}$.
* **Model:** Assumes an internal one-layer density profile: $\rho(r)=\rho_0 \exp(-r/L)$, where $\rho_0=18000\,\text{kg/m}^3$ and $L=6500\,\text{km}$.
* **Root-Finding Challenge:** The mass equation $M=4\pi\int_0^R \rho(r)r^2\,dr$ must be solved numerically for $R$, which presents a challenge since the solution cannot be approached from the negative side (mass must be non-negative).

### 7. Complex Transcendental Equation Solver (NEW)

Application of a root-finding algorithm (e.g., **Bisection** or **Brent's method**) to solve a complex transcendental equation.
* **Equation:** Find the roots of the equation $f(x) = \sqrt{x^2 + 1} + e^x \sin x - 7 = 0$.
* **Task 1:** Find the first solution within the interval $[0, 2]$.
* **Task 2:** Find all roots within the larger interval $(0, 16)$.

---

## ⚙️ Technologies Used

* **Python 3**
* **NumPy** (For numerical arrays and basic functions)
* **Matplotlib** (For plotting and visualizing force fields, orbits, and convergence)
* **Sympy** (For symbolic derivatives and simplifications, crucial for Newton-Raphson and Halley's methods)
* **Jupyter Notebook**

---

## 📈 Skills Demonstrated

* Implementation of **iterative numerical algorithms** (Newton, Halley, Secant, etc.)
* Application of **computational methods to physics problems** (Orbital mechanics, Electromagnetism, Planetary Science).
* **Visualization and analysis** of results, including convergence rate studies.
* Code documentation and reproducibility.

---

## 📚 Course Context

This portfolio was created as part of the **Computational Methods** course, aimed at applying numerical algorithms to solve scientific and engineering problems with precision and efficiency.

## 🧑‍💻 Author

Carolina Andrea Rodas Castañeda
Course: Computational Methods
2025


