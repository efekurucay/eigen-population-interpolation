# eigen-population-interpolation

Welcome to the `eigen-population-interpolation` repository — a compact but comprehensive showcase of linear algebra applications in recursion, dynamical systems, and polynomial interpolation.

This repository contains solutions to **MAT 222 - Linear Algebra** Assignment 1, focused on:

- 📊 **Recurrence Relations via Matrices**  
- 🐿 **Predator-Prey Population Dynamics (Discrete Systems)**  
- 📊 **Lagrange Polynomial Interpolation**

---

## 🔍 Problem Overview

### ✅ Problem 1 – Recurrence Relation & Eigenvalue Method
Solve the linear recurrence:
```math
x_0 = 2, x_1 = 1, x_{n+2} = -x_{n+1} + 2x_n
```
- Reformulated into matrix form
- Solved using eigenvalues and eigenvectors
- General term:
```math
x_n = (5/3) + (1/3)(-2)^n
```

**Notebook:** `Problem1_EigenSolution.ipynb`

---

### ✅ Problem 2 – Discrete Predator-Prey Dynamics
Given initial populations and matrix `A`:
```plaintext
A = [[0.3, 0.4],
     [-0.3, 1.1]]
x0 = 30, y0 = 35
```
- Found eigenvalues
- Analyzed long-term behavior:
  - Both populations tend to 0
  - System dies out over time

**Notebook:** `Problem2_PopulationDynamics.ipynb`

---

### ✅ Problem 3 – Lagrange Interpolation
Interpolated a degree ≤ 3 polynomial through:
```plaintext
(-4,-26), (-3,-15), (1,9), (2,10)
```
- Constructed Lagrange basis polynomials
- Combined to obtain unique polynomial `P(x)`

**Notebook:** `Problem3_LagrangeInterpolation.ipynb`

---

## 📁 Repository Structure

```
eigen-population-interpolation/
|
|├— Problem1_EigenSolution.ipynb
|├— Problem2_PopulationDynamics.ipynb
|├— Problem3_LagrangeInterpolation.ipynb
|├— results/
|│   └— simplified_polynomial.pdf
|└— README.md
```

---

## 📌 Tools Used
- Python (NumPy, SymPy, Matplotlib)
- Jupyter Notebook
- LaTeX for math formatting

---

## 💌 Feedback
Fork, explore and submit PRs or issues if you'd like to contribute or ask questions!
