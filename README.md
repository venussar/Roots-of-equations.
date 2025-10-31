#  Roots — Computational Methods Portfolio

Developed by **Carolina Andrea Rodas Castañeda**  
as part of the **Computational Methods** coursework.

---

##  Overview
This repository contains a collection of numerical analysis projects focused on **root-finding algorithms** and their applications to physics and mathematics problems.  
Each exercise explores different iterative methods such as **Newton-Raphson**, **Halley’s Method**, **Secant Method**, **Fixed-Point Iteration**, and more.

The projects were developed using Python as part of the *Computational Methods* course.

---

##  Projects

### 1. Halley’s Method — Root Convergence
Implementation of **Halley’s Method**, which uses both first and second derivatives to achieve **cubic convergence**.  
- Finds the first positive root of the function:  
  \[
  f(x) = \sin(x) + \cos(1 + x^2) - 1
  \]
- Examines how convergence depends on the **tolerance** value.

---

### 2. Electric Force of a Charged Ring
Simulation of the **electric force** exerted by a uniformly charged ring on a point charge.  
- Computes the force:
  \[
  F = \frac{1}{4\pi\epsilon_0}\frac{qQx}{(x^2 + a^2)^{3/2}}
  \]
- Uses the **Newton-Raphson** and **Fixed-Point** methods to find \(x\) where \(F = 1.25\,N\).  
- Studies how the ring’s radius affects the resulting force.

---

### 3. Kepler’s Equation — Halley’s Comet
Numerical solution of **Kepler’s Equation** to find the **eccentric anomaly** \(E\):  
\[
M = E - e\sin(E)
\]
- Applies the **Bisection**, **Newton**, and **Secant** methods.  
- Analyzes the orbit of **Halley’s Comet** using its real orbital parameters.  
- Plots \(E(t)\) for a full orbital period.

---

### 4. Fraunhofer Diffraction by a Slit
Computation and visualization of the **diffraction intensity pattern**:
\[
I(\theta) = I_0 \left[\frac{\sin(\pi W \sin\theta / \lambda)}{\pi W \sin\theta / \lambda}\right]^2
\]
- Calculates and plots both \(I(x)\) and \(I'(x)\).  
- Uses **Secant** and **Regula Falsi** methods to find the half-intensity points and maxima.

---

### 5. Lagrange Point \(L_1\) — Earth-Moon System
Numerical computation of the **Lagrange point \(L_1\)** between the Earth and the Moon:  
\[
\frac{GM}{r^2} - \frac{Gm}{(R - r)^2} = \omega^2 r
\]
- Solved using **Newton’s Method** and **Secant Method**.  
- Determines the equilibrium distance \(r\) where gravitational and centrifugal forces balance.  
- Uses physical parameters for the Earth-Moon system.

---

##  Technologies Used
- **Python 3**
- **NumPy**
- **Matplotlib**
- **Sympy** (for symbolic derivatives and simplifications)
- **Jupyter Notebook**

---

##  Skills Demonstrated
- Implementation of **iterative numerical algorithms**  
- Application of **computational methods to physics problems**  
- **Visualization and analysis** of results  
- Code documentation and reproducibility

---

##  Course Context
This portfolio was created as part of the **Computational Methods** course,  
aimed at applying numerical algorithms to solve scientific and engineering problems with precision and efficiency.

---

##  Author
**Carolina Andrea Rodas Castañeda**  
*Course: Computational Methods*  
 *2025*

---
