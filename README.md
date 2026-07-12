<div align="center">

# Computational Numerical Methods  
## Interactive Masterclass for Chemical Engineering

A complete, browser-based numerical methods learning platform that connects mathematical theory, hand calculations, engineering interpretation, MATLAB implementation, interactive computation, and exam preparation.

[![Live Website](https://img.shields.io/badge/Live_Website-GitHub_Pages-1f6feb?style=for-the-badge&logo=github)](https://kami80.github.io/numerical-methods-lecture/)
[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111)](https://developer.mozilla.org/docs/Web/JavaScript)
[![KaTeX](https://img.shields.io/badge/Math-KaTeX-21b8c7?style=for-the-badge)](https://katex.org/)
[![MATLAB](https://img.shields.io/badge/Examples-MATLAB-e16737?style=for-the-badge)](https://www.mathworks.com/products/matlab.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-3da639?style=for-the-badge)](LICENSE)

[Open the lecture](https://kami80.github.io/numerical-methods-lecture/) ·
[Open the PDE companion](https://kami80.github.io/numerical-methods-lecture/pde.html) ·
[Report an issue](https://github.com/Kami80/numerical-methods-lecture/issues) ·
[Contribute](#contributing)

</div>

---

## Overview

**Computational Numerical Methods — Interactive Masterclass** is an educational web project designed for engineering students who need more than a static collection of equations.

The repository combines:

- rigorous numerical-analysis foundations;
- method-selection guidance;
- fully worked, step-by-step engineering examples;
- MATLAB implementations;
- live browser-based numerical solvers;
- automatic tables, plots, heat maps, and convergence studies;
- adaptive quizzes and topic-level feedback;
- a personal study dashboard with locally saved progress;
- advanced exam-workshop problems with complete solutions;
- a dedicated companion lecture for partial differential equations.

The main examples are written from a **chemical-engineering perspective**, while the underlying methods are equally relevant to mechanical, civil, electrical, petroleum, materials, environmental, and applied-science programs.

> **No installation, build system, backend, or account is required.**  
> Open the website and start studying.

---

## Table of Contents

- [Why This Project Exists](#why-this-project-exists)
- [Highlights](#highlights)
- [Course at a Glance](#course-at-a-glance)
- [Main Lecture Content](#main-lecture-content)
- [Advanced PDE Companion](#advanced-pde-companion)
- [Interactive Laboratories](#interactive-laboratories)
- [Learning Dashboard and Mastery System](#learning-dashboard-and-mastery-system)
- [MATLAB Integration](#matlab-integration)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Using the Lecture](#using-the-lecture)
- [GitHub Pages Deployment](#github-pages-deployment)
- [Local Data and Privacy](#local-data-and-privacy)
- [Accessibility and Responsive Design](#accessibility-and-responsive-design)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [Suggested Development Roadmap](#suggested-development-roadmap)
- [Academic Use](#academic-use)
- [License](#license)
- [Author](#author)

---

## Why This Project Exists

Numerical methods are often taught in disconnected layers:

1. formulas are introduced without enough interpretation;
2. hand calculations are shown without scalable implementation;
3. MATLAB code is provided without explaining the algorithm;
4. final answers are presented without verification;
5. students memorize procedures without learning how to choose a method.

This project unifies those layers into one structured learning environment:

```text
Physical problem
      ↓
Mathematical model
      ↓
Method selection
      ↓
Discretization or iteration
      ↓
Hand calculation
      ↓
MATLAB implementation
      ↓
Browser-based experiment
      ↓
Error, stability, and convergence checks
      ↓
Engineering interpretation
```

The central principle is that a numerical answer is useful only when the student can explain:

- why the method is appropriate;
- what assumptions were made;
- how the approximation was constructed;
- whether the algorithm converged;
- how sensitive the result is to step size or grid size;
- whether the final result is physically reasonable.

---

## Highlights

### Comprehensive engineering lecture

The main page contains a complete guided course with:

- **20 guided lecture chapters**;
- **29 worked and practice problems**;
- **7 interactive numerical laboratories**;
- **12 complete exam-workshop solutions**;
- a **30-question adaptive mastery bank**;
- numerical-analysis foundations and method-selection guidance;
- ODE, BVP, finite-difference, regression, and linear-system methods.

### Interactive study environment

Students can:

- search concepts, formulas, examples, and methods;
- expand or collapse worked-solution steps;
- switch between dark and light themes;
- enable focus mode;
- increase text size;
- print the lecture or save it as a PDF;
- copy MATLAB code directly;
- write chapter-specific notes;
- mark chapters as completed;
- track solved exam problems;
- continue from the next unfinished chapter;
- use a configurable daily focus timer;
- inspect recent study activity;
- retain progress in the browser.

### Live numerical computation

The browser laboratories execute numerical algorithms directly with JavaScript and generate:

- iteration tables;
- residual and error values;
- numerical solution curves;
- convergence plots;
- finite-difference temperature profiles;
- two-dimensional heat maps;
- regression fits;
- stability feedback;
- method comparisons.

### Dedicated PDE masterclass

The companion `pde.html` page expands the project beyond introductory finite differences and covers:

- PDE classification;
- elliptic, parabolic, and hyperbolic equations;
- Laplace and Poisson equations;
- explicit and implicit heat solvers;
- Crank–Nicolson;
- alternating-direction implicit methods;
- method of lines;
- wave equations;
- PSOR;
- boundary-condition discretization;
- advection–reaction systems;
- matrix assembly and solver selection;
- verification, convergence, and error analysis;
- interactive simulation and graded review.

---

## Course at a Glance

| Area | What Students Learn | Included Learning Tools |
|---|---|---|
| Numerical foundations | Error, conditioning, consistency, convergence, stability, stiffness | Concept cards, verification workflow, method-selection guide |
| Linear systems | Direct and iterative solution strategies | Full derivations, elimination tables, live solver |
| Initial-value ODEs | Taylor and Runge–Kutta families | Hand calculations, MATLAB code, interactive comparison |
| Boundary-value problems | Shooting and finite differences | Secant updates, matrix formulation, verification |
| PDEs | Steady and transient transport equations | Stencils, stability analysis, heat simulation |
| Regression | Parameter estimation from engineering data | Least-squares derivation, automatic fit and plot |
| Exam preparation | Method selection, computation, checking | Practice bank, adaptive quiz, 12 full workshop solutions |
| Study management | Progress and retention | Dashboard, notes, streak, timer, local history |

---

## Main Lecture Content

The main lecture is located in [`index.html`](index.html).

### 1. Student-Centered Learning Path

The course begins with multiple study routes, including:

- fast exam review;
- full concept mastery;
- computation-focused practice;
- progressive movement from theory to advanced exam problems.

The recommended workflow for each chapter is:

1. classify the mathematical problem;
2. identify assumptions and governing equations;
3. select and justify the numerical method;
4. perform the calculation;
5. verify the numerical and physical result.

### 2. Foundations of Numerical Analysis

Core concepts include:

- absolute and relative error;
- truncation error;
- round-off error;
- local and global error;
- consistency;
- convergence;
- stability;
- conditioning;
- residuals;
- stiffness;
- step-size and mesh refinement;
- observed order of accuracy;
- verification versus validation.

### 3. Numerical Method Selection

A decision-oriented section helps students choose among:

- direct linear solvers;
- iterative linear solvers;
- Taylor methods;
- Runge–Kutta methods;
- shooting methods;
- finite-difference methods;
- regression methods.

The emphasis is on recognizing the **problem type before choosing the algorithm**.

### 4. Linear Algebra Methods

#### Gaussian Elimination

- augmented-matrix formulation;
- forward elimination;
- pivot operations;
- partial pivoting;
- back substitution;
- residual checking;
- MATLAB implementation;
- engineering-system applications.

#### Gauss–Jordan Method

- complete row reduction;
- reduced row-echelon form;
- systematic variable isolation;
- comparison with Gaussian elimination;
- worked calculations and MATLAB code.

#### Gauss–Seidel Method

- iterative equation rearrangement;
- initial guesses;
- convergence criteria;
- diagonal dominance;
- stopping tolerances;
- iteration tables;
- engineering interpretation.

### 5. Taylor Series Methods

- second-order Taylor method;
- third-order Taylor method;
- derivative construction;
- truncation-error interpretation;
- step-by-step numerical examples;
- accuracy comparison;
- MATLAB implementation.

### 6. Runge–Kutta Methods

#### RK2

- Heun predictor–corrector method;
- midpoint RK2;
- slope averaging;
- nonlinear reaction-kinetics examples;
- error behavior and MATLAB implementation.

#### RK3

- stage construction;
- weighted slope combination;
- full intermediate calculations;
- engineering ODE examples;
- implementation guidance.

#### RK4

- classical fourth-order formulation;
- detailed \(k_1\), \(k_2\), \(k_3\), and \(k_4\) calculations;
- multi-step solution tables;
- error comparison;
- nonlinear engineering applications;
- MATLAB implementation.

### 7. Shooting Method

- conversion of a BVP into an IVP;
- unknown initial-slope estimation;
- RK integration;
- secant correction;
- convergence monitoring;
- boundary residual verification;
- MATLAB workflow.

### 8. Finite Difference Method — 1D

- derivative approximations;
- central-difference formulas;
- node generation;
- Dirichlet and related boundary conditions;
- tridiagonal coefficient matrices;
- matrix solution;
- mesh refinement;
- steady heat- and mass-transfer applications.

### 9. Finite Difference Method — 2D

- two-dimensional domain discretization;
- five-point stencil;
- node numbering;
- coefficient-matrix assembly;
- Laplace and Poisson equations;
- internal heat generation;
- boundary-value treatment;
- temperature-field interpretation;
- contour and heat-map visualization.

### 10. Regression Analysis

- linear least-squares regression;
- normal equations;
- slope and intercept derivation;
- residuals;
- coefficient of determination;
- engineering parameter estimation;
- automatic browser-based fitting and plotting;
- MATLAB implementation.

### 11. Convergence Laboratory

Students compare:

- Euler;
- Heun RK2;
- midpoint RK2;
- classical RK4.

The laboratory repeatedly halves the step size and reports:

- final numerical error;
- error ratios;
- observed order;
- log–log convergence behavior.

---

## Advanced PDE Companion

The dedicated PDE lecture is located in [`pde.html`](pde.html).

### Learning roadmap

The PDE page guides the student through the full process:

```text
Classify the PDE
      ↓
Identify initial and boundary conditions
      ↓
Choose spatial and temporal discretization
      ↓
Derive the stencil
      ↓
Check consistency and stability
      ↓
Assemble and solve the algebraic system
      ↓
Verify using refinement and physical checks
```

### PDE classification

The lecture distinguishes:

| PDE Class | Canonical Behavior | Typical Engineering Example |
|---|---|---|
| Elliptic | Steady spatial equilibrium | Steady heat conduction, potential flow |
| Parabolic | Diffusive time evolution | Transient heat conduction, molecular diffusion |
| Hyperbolic | Wave or transport propagation | Vibrations, pressure waves, wave equations |

### Finite-difference grid construction

- one- and two-dimensional grids;
- spatial and temporal indexing;
- forward, backward, and central approximations;
- stencil interpretation;
- grid resolution;
- local truncation error.

### Laplace equation

- steady-state conduction without volumetric generation;
- five-point stencil;
- boundary-node treatment;
- iterative solution;
- convergence checks.

### Poisson equation

- source and generation terms;
- internal heat generation;
- coefficient-matrix construction;
- physical interpretation of source strength.

### Explicit transient heat method

- FTCS discretization;
- time marching;
- Fourier number;
- conditional stability;
- practical time-step limits;
- transient temperature evolution.

### Implicit transient heat method

- backward-time discretization;
- algebraic system at every time step;
- unconditional stability discussion;
- comparison with explicit schemes.

### Crank–Nicolson method

- temporal averaging;
- second-order time accuracy;
- matrix form;
- stability and oscillation considerations;
- comparison with explicit and fully implicit methods.

### Alternating-Direction Implicit Method

- splitting multidimensional systems;
- alternating line solves;
- computational benefits for 2D diffusion;
- implementation logic.

### Method of Lines

- spatial semi-discretization;
- conversion of a PDE into an ODE system;
- integration with ODE solvers;
- connection to reaction–diffusion models.

### Wave equation

- central differences in space and time;
- initial displacement and velocity;
- Courant condition;
- propagation and stability.

### PSOR

- point-wise iterative updates;
- relaxation factor;
- acceleration of steady PDE solutions;
- residual-based stopping criteria.

### Boundary discretization

- Dirichlet conditions;
- Neumann conditions;
- Robin or convective conditions;
- ghost-node concepts;
- one-sided approximations;
- boundary consistency.

### Advection–reaction systems

- convection, diffusion, and reaction competition;
- upwind and centered formulations;
- numerical oscillations;
- Peclet-number interpretation;
- stability and artificial diffusion.

### Matrix structure and solver selection

- sparse systems;
- tridiagonal systems;
- direct versus iterative methods;
- matrix conditioning;
- residual monitoring.

### Verification and error analysis

- grid-independence studies;
- time-step refinement;
- observed order;
- conservation checks;
- comparison with analytical limits;
- residual norms;
- numerical versus modeling error.

---

## Interactive Laboratories

All laboratories run locally in the browser using vanilla JavaScript.

### ODE Solver Laboratory

Users can modify the model, initial values, interval, and step size, then compare numerical trajectories from multiple methods.

Typical outputs include:

- solution table;
- final value;
- method comparison;
- error behavior;
- plotted response.

### Linear-System Laboratory

The live solver demonstrates matrix-based solution logic and allows students to connect elimination steps with the final solution and residual.

### 1D Finite-Difference Laboratory

Students can change physical and numerical parameters for a steady transport problem and inspect:

- node locations;
- coefficient matrix behavior;
- temperature or concentration profile;
- discretization response.

### 2D Heat Laboratory

The page computes and renders a two-dimensional field as a browser-generated heat map.

Students can investigate:

- boundary-temperature effects;
- internal generation;
- grid resolution;
- convergence of the iterative solution;
- physical symmetry and gradients.

### Regression Laboratory

Experimental data can be transformed into:

- least-squares parameters;
- fitted values;
- residual measures;
- an automatically drawn regression plot.

### Convergence Laboratory

The convergence tool estimates numerical order by comparing errors across progressively refined step sizes.

### PDE Heat Simulator

The PDE companion includes a live one-dimensional transient heat simulator for comparing:

- explicit FTCS;
- Crank–Nicolson;
- stability behavior;
- diffusion over time;
- the effect of grid and time-step settings.

---

## Learning Dashboard and Mastery System

### Personal study dashboard

The dashboard tracks:

- completed chapters;
- overall course completion;
- best quiz score;
- average quiz score;
- number of quiz attempts;
- exam-workshop problems marked as solved;
- study-day streak;
- number of chapters containing notes;
- topic-level mastery;
- recent learning activity.

### Continue-studying system

The lecture identifies the next unfinished chapter and creates a direct resume link.

A random-incomplete-chapter tool is also provided for revision sessions.

### Daily focus timer

Students can choose a study target of:

- 15 minutes;
- 30 minutes;
- 45 minutes;
- 60 minutes.

Elapsed time and remaining time are saved locally.

### Chapter notes

A notes drawer stores separate notes for the active chapter.

Notes are:

- automatically saved;
- retained in the current browser;
- independent from chapter-completion resets.

### Adaptive mastery quiz

The 30-question bank supports filtering by:

- topic;
- difficulty;
- quiz length.

The quiz provides:

- optional timing;
- hints;
- immediate answer feedback;
- mathematical explanations;
- links to relevant chapters;
- streak tracking;
- questions marked for review;
- topic-by-topic result analysis;
- missed-question review;
- saved attempt history.

### Advanced exam workshop

The workshop contains **12 complete solutions** organized by topic and difficulty.

Each solution includes:

1. problem classification;
2. governing formula;
3. numerical substitutions;
4. intermediate calculations;
5. final result;
6. verification.

Students can:

- filter problems by topic;
- filter by difficulty;
- open a random problem;
- reveal or hide solutions;
- mark problems as solved;
- retain solved status locally.

---

## MATLAB Integration

MATLAB examples are embedded throughout the lecture to connect hand calculations with reproducible engineering computation.

Code sections include:

- input and parameter definition;
- algorithm implementation;
- iteration loops;
- stopping criteria;
- matrix construction;
- plotting;
- error calculation;
- formatted output.

A copy button is automatically added to code blocks for convenient transfer into MATLAB.

> MATLAB code is presented for study and execution in MATLAB or GNU Octave.  
> The website itself does not execute MATLAB. Its live laboratories use JavaScript implementations of the numerical algorithms.

---

## Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Semantic lecture structure and content |
| CSS3 | Responsive layout, themes, cards, tables, print styling, and visualization |
| Vanilla JavaScript | Solvers, plots, quizzes, search, dashboard, notes, and progress tracking |
| KaTeX | Fast mathematical equation rendering |
| HTML Canvas | Numerical plots and heat-map visualization |
| Web Storage API | Local progress, notes, quiz history, timer, and activity |
| MATLAB | Educational implementations and engineering workflows |
| GitHub Pages | Static website hosting |

### External resources

The project loads:

- Google Fonts;
- KaTeX CSS and JavaScript from a CDN.

Because these resources are remote, an internet connection is recommended for the intended typography and equation rendering. The core HTML, CSS, and JavaScript content remains in the repository.

---

## Project Structure

```text
numerical-methods-lecture/
│
├── index.html      # Main numerical-methods masterclass
├── pde.html        # Advanced PDE companion lecture
├── README.md       # Project documentation
└── LICENSE         # MIT License
```

The current project intentionally uses a compact architecture: styles, lecture markup, and JavaScript logic are embedded in the two HTML pages.

### Main-page responsibilities

```text
index.html
├── Numerical-analysis foundations
├── Linear-system methods
├── ODE methods
├── Boundary-value methods
├── Finite differences
├── Regression
├── MATLAB examples
├── Interactive laboratories
├── Mastery quiz
├── Exam workshop
└── Study dashboard
```

### PDE-page responsibilities

```text
pde.html
├── PDE classification
├── Spatial discretization
├── Elliptic equations
├── Parabolic equations
├── Hyperbolic equations
├── Stability and convergence
├── Boundary conditions
├── Advection–reaction models
├── Linear solvers
├── Interactive PDE laboratory
├── Practice problems
├── Graded quiz
└── Reference sheet
```

---

## Getting Started

### Option 1 — Use the hosted website

Open:

```text
https://kami80.github.io/numerical-methods-lecture/
```

For the PDE companion:

```text
https://kami80.github.io/numerical-methods-lecture/pde.html
```

### Option 2 — Clone the repository

```bash
git clone https://github.com/Kami80/numerical-methods-lecture.git
cd numerical-methods-lecture
```

Then open `index.html` in a modern browser.

### Option 3 — Run a local web server

A local server is recommended for consistent browser behavior.

#### Python

```bash
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

#### Node.js

```bash
npx serve .
```

#### Visual Studio Code

Install the **Live Server** extension, right-click `index.html`, and select:

```text
Open with Live Server
```

---

## Using the Lecture

### Recommended first-time path

1. Open the **Learning Path**.
2. Review **Foundations of Numerical Analysis**.
3. Use **Method Selection** before studying individual algorithms.
4. Complete one linear-system chapter.
5. Study Taylor and Runge–Kutta methods.
6. compare methods in the **Convergence Laboratory**;
7. continue to shooting and finite differences;
8. complete regression and browser laboratories;
9. take a targeted mastery quiz;
10. finish with the advanced exam workshop;
11. continue to the PDE companion.

### Recommended chapter workflow

For every numerical method:

1. read the learning objectives;
2. identify the problem class;
3. study the governing formulas;
4. reproduce the worked example by hand;
5. run the MATLAB code;
6. modify parameters in the browser laboratory;
7. perform an error or refinement check;
8. write a one-paragraph engineering interpretation;
9. mark the chapter complete.

### Search

Use the lecture search box or:

```text
Ctrl + K
```

On macOS:

```text
Command + K
```

Search results link directly to matching chapters.

### Print or save as PDF

Use the **Print** button in the study toolbar, then choose **Save as PDF** from the browser print dialog.

---

## GitHub Pages Deployment

This project is fully compatible with GitHub Pages because it is a static website.

### Deploy from the GitHub interface

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch.
6. Select the `/ (root)` folder.
7. Save the configuration.

The site URL follows this pattern:

```text
https://<username>.github.io/<repository-name>/
```

For this repository:

```text
https://kami80.github.io/numerical-methods-lecture/
```

### Update the website

After changing the files:

```bash
git add index.html pde.html README.md
git commit -m "Improve numerical methods lecture"
git push origin main
```

GitHub Pages will deploy the updated static files from the configured branch.

---

## Local Data and Privacy

The project has:

- no backend;
- no user registration;
- no database;
- no analytics service included in the lecture code;
- no cloud synchronization of study records.

The following information is stored only in the browser through `localStorage`:

- selected theme;
- completed chapters;
- notes;
- quiz history;
- missed-question history;
- solved exam problems;
- focus-timer state;
- study days;
- recent activity.

### Important consequences

- clearing browser site data removes saved progress;
- progress does not automatically transfer between devices;
- private or sensitive information should not be placed in study notes;
- hosting the site does not require a server-side application.

---

## Accessibility and Responsive Design

The lecture includes features intended to improve usability:

- semantic headings and sections;
- a skip-to-content link;
- keyboard-accessible controls;
- labeled search and navigation elements;
- responsive sidebar behavior;
- mobile navigation;
- larger-text mode;
- focus mode;
- light and dark themes;
- horizontal scrolling for wide formulas and tables;
- print-friendly output;
- expandable solution steps;
- descriptive labels for interactive controls.

Contributions that improve keyboard navigation, contrast, screen-reader output, reduced-motion behavior, and accessible canvas alternatives are especially valuable.

---

## Browser Support

Recommended browsers:

- Google Chrome;
- Microsoft Edge;
- Mozilla Firefox;
- Safari.

The project relies on modern browser features including:

- `localStorage`;
- `CanvasRenderingContext2D`;
- optional chaining;
- template literals;
- modern CSS Grid and Flexbox;
- the Clipboard API with a fallback.

For the best experience, use a current browser version with JavaScript enabled.

---

## Contributing

Contributions are welcome in the form of:

- corrected equations;
- improved numerical derivations;
- additional engineering examples;
- better MATLAB implementations;
- new browser laboratories;
- quiz questions;
- verification tests;
- accessibility improvements;
- responsive-design fixes;
- documentation improvements;
- typo and notation corrections.

### Contribution workflow

1. Fork the repository.
2. Create a focused branch:

```bash
git checkout -b feature/new-numerical-lab
```

3. Make and test the changes.
4. Commit with a clear message:

```bash
git commit -m "Add interactive Newton-Raphson laboratory"
```

5. Push the branch:

```bash
git push origin feature/new-numerical-lab
```

6. Open a pull request.

### Content contribution checklist

Before submitting educational content, verify that:

- symbols are defined before use;
- equations render correctly in KaTeX;
- units are consistent;
- intermediate values are reproducible;
- code output agrees with the hand calculation;
- the final answer satisfies the governing equation or residual check;
- stability restrictions are stated where applicable;
- tables remain readable on mobile;
- new interactive controls have accessible labels;
- the contribution does not introduce copyrighted material without permission.

### JavaScript contribution checklist

- use clear variable names;
- keep algorithms readable for students;
- validate user inputs;
- avoid silent numerical failures;
- display useful error or stability messages;
- separate computational logic from rendering where practical;
- test both dark and light themes;
- test at desktop and mobile widths;
- preserve local-storage compatibility when changing saved-data keys.

---

## Suggested Development Roadmap

Potential future enhancements include:

- modularizing embedded CSS and JavaScript;
- adding automated numerical regression tests;
- adding GitHub Actions for HTML validation and link checking;
- adding root-finding methods such as bisection, secant, and Newton–Raphson;
- adding Jacobi, SOR, and conjugate-gradient comparisons;
- adding adaptive Runge–Kutta methods;
- adding stiff ODE solvers;
- adding nonlinear systems;
- adding numerical integration and differentiation;
- adding eigenvalue methods;
- adding finite-volume and finite-element introductions;
- adding CSV import and export for laboratory data;
- exporting quiz and progress reports;
- adding downloadable MATLAB files;
- adding GNU Octave compatibility tests;
- providing offline support through a Progressive Web App;
- adding multilingual lecture support;
- adding automated accessibility auditing;
- adding reference solutions for more industrial chemical-engineering models.

---

## Academic Use

This repository is suitable for:

- university lectures;
- tutorial sessions;
- teaching-assistant workshops;
- independent study;
- exam preparation;
- engineering-computation demonstrations;
- introductory scientific-computing projects.

The project is an educational aid and should not replace:

- instructor guidance;
- independent derivation;
- verification against trusted references;
- professional engineering judgment;
- validated industrial simulation software.

For assessed coursework, follow the academic-integrity rules of the relevant institution and clearly cite reused material.

---

## License

This project is distributed under the [MIT License](LICENSE).

You may use, copy, modify, merge, publish, and distribute the software under the terms stated in the license.

---

## Author

**Kamyab Safaei**  
Chemical Engineering M.Sc. student, University of Tehran

GitHub: [@Kami80](https://github.com/Kami80)

Repository:

```text
https://github.com/Kami80/numerical-methods-lecture
```

---

## Acknowledgments

This project is inspired by the standard numerical-methods curriculum taught in engineering and applied-science programs, including:

- numerical analysis;
- engineering mathematics;
- chemical reaction engineering;
- heat transfer;
- transport phenomena;
- process modeling;
- scientific computing.

Its educational goal is to make numerical methods easier to **derive, calculate, implement, test, and interpret**.

---

<div align="center">

### Learn the method. Run the algorithm. Verify the answer. Interpret the physics.

If this repository supports your studies or teaching, consider giving it a star.

[![GitHub stars](https://img.shields.io/github/stars/Kami80/numerical-methods-lecture?style=social)](https://github.com/Kami80/numerical-methods-lecture/stargazers)

</div>
