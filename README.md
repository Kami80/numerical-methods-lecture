# Numerical Methods Handbook for Engineers

An interactive educational website covering the most important numerical methods used in engineering, applied mathematics, and scientific computing.

This project was developed as a comprehensive learning resource containing:

- Detailed theoretical explanations
- Step-by-step derivations
- Fully worked hand-calculation examples
- MATLAB implementations
- Engineering applications
- Interactive expandable sections
- Visual representations of numerical algorithms

---

## Website Preview

This handbook covers numerical methods commonly taught in:

- Chemical Engineering
- Mechanical Engineering
- Civil Engineering
- Electrical Engineering
- Applied Mathematics
- Computational Science

The goal is to bridge the gap between theory, hand calculations, and practical MATLAB implementation.

---

# Topics Covered

## Initial Value Problems (IVPs)

### Euler Method
- Forward Euler formulation
- Local and global truncation error
- Worked examples
- MATLAB implementation

### Taylor Series Method
- 2nd Order Taylor Method
- 3rd Order Taylor Method
- Higher-order derivative derivation
- Error comparison
- MATLAB implementation

### Runge-Kutta Methods

#### RK2 (Heun Method)
- Predictor-Corrector formulation
- Slope averaging concept
- Worked engineering examples
- MATLAB implementation

#### RK4 Method
- Classical fourth-order Runge-Kutta
- Detailed k₁, k₂, k₃, k₄ derivation
- Multi-step calculations
- MATLAB implementation

---

## Boundary Value Problems (BVPs)

### Shooting Method
- Conversion of BVP to IVP
- RK4 integration
- Secant iteration
- Convergence analysis
- MATLAB implementation

### Finite Difference Method (1D)
- Central difference approximation
- Boundary conditions
- Tridiagonal matrix formulation
- Gaussian elimination solution
- MATLAB implementation

### Finite Difference Method (2D)
- Laplace Equation
- Poisson Equation
- Five-point stencil
- Node numbering
- Matrix assembly
- Gaussian elimination solution
- Temperature contour interpretation
- MATLAB implementation

---

## Linear Algebra Methods

### Gaussian Elimination
- Matrix formulation
- Forward elimination
- Partial pivoting
- Back substitution
- Numerical stability considerations
- MATLAB implementation

---

# Features

## Detailed Derivations

Every method includes:

- Mathematical foundation
- Formula derivation
- Engineering interpretation
- Numerical implementation

---

## Worked Examples

Examples are solved completely by hand.

Each example includes:

- Problem statement
- Governing equations
- Step-by-step calculations
- Final numerical solution
- Verification

---

## MATLAB Code

Every numerical method includes:

- Fully commented MATLAB code
- Educational explanations
- Variable descriptions
- Plot generation
- Error analysis

---

## Interactive Layout

The website uses expandable sections through HTML `<details>` tags.

Benefits:

- Cleaner interface
- Easier navigation
- Reduced scrolling
- Better mobile experience

---

# Engineering Applications

The examples are inspired by real engineering systems such as:

### Chemical Engineering

- Batch reactor kinetics
- Concentration decay
- Nonlinear reaction systems

### Heat Transfer

- Steady-state conduction
- Heat generation
- Temperature distributions
- Finite difference solutions

### Transport Phenomena

- Diffusion equations
- Boundary value problems

### Mathematical Modeling

- Population growth
- Logistic equations
- Dynamic systems

---

# Numerical Methods Included

| Method | Type | MATLAB |
|----------|----------|----------|
| Euler | IVP | ✓ |
| Taylor Series | IVP | ✓ |
| RK2 (Heun) | IVP | ✓ |
| RK4 | IVP | ✓ |
| Shooting Method | BVP | ✓ |
| FDM 1D | BVP | ✓ |
| FDM 2D | PDE | ✓ |
| Gaussian Elimination | Linear Algebra | ✓ |

---

# Software Used

- HTML5
- CSS3
- JavaScript
- MathJax
- MATLAB

---

# Project Structure

```text
numerical-methods-website/
│
├── index.html
├── style.css
├── script.js
├── images/
│
└── README.md
```

---

# Learning Objectives

After studying this handbook, students should be able to:

- Solve ordinary differential equations numerically
- Solve boundary value problems
- Construct finite difference approximations
- Implement RK methods
- Apply Gaussian elimination
- Write MATLAB programs for numerical algorithms
- Analyze numerical error
- Interpret engineering results

---

# Example Topics

### RK4 Example

Nonlinear reaction kinetics:

```math
\frac{dC_A}{dt}=-0.5C_A^2
```

---

### Shooting Method Example

Boundary value problem:

```math
y''-4y=0
```

with

```math
y(0)=1
```

and

```math
y(1)=e^2
```

---

### FDM Example

Heat conduction:

```math
\frac{d^2T}{dx^2}=-10
```

with prescribed boundary temperatures.

---

# Future Improvements

Planned additions:

- Newton-Raphson Method
- Bisection Method
- Secant Method
- Gauss-Seidel Method
- Jacobi Method
- Crank-Nicolson Method
- Explicit PDE Solvers
- Implicit PDE Solvers
- Finite Element Method (FEM)
- Interactive calculators
- Automatic MATLAB code generation

---

# Deployment

This website is hosted using GitHub Pages.

Example deployment URL:

```text
https://yourusername.github.io/numerical-methods-website/
```

---

# Contributing

Contributions are welcome.

Possible contributions include:

- Additional worked examples
- MATLAB improvements
- New numerical methods
- UI/UX enhancements
- Error corrections

---

# License

This project is released under the MIT License.

You are free to:

- Use
- Modify
- Share
- Distribute

with proper attribution.

---

# Author

Developed as an educational numerical methods handbook for engineering students and professionals.

---

# Acknowledgments

This handbook draws upon concepts commonly taught in:

- Numerical Methods for Engineers
- Applied Numerical Analysis
- Computational Methods
- Engineering Mathematics
- Heat Transfer
- Chemical Reaction Engineering

and aims to provide a practical bridge between theory and computation.

---

## Star the Repository

If you found this project useful, consider giving it a ⭐ on GitHub.
