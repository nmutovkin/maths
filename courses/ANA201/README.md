# ANA201 Ordinary Differential Equations

How to solve the standard classes of ordinary differential equations, and how
to understand the behaviour of solutions when no formula is available.
Part of the [analysis track](../../curriculum/02-analysis.md).

## About this course

**Prerequisites.** [ANA101 Calculus I](../ANA101/README.md) and ALG101 Linear
Algebra I. Two topics that are not covered there are taught in this course:

- complex numbers and Euler's formula $e^{i\theta} = \cos\theta + i\sin\theta$
  (Lesson 0.1), needed for oscillating solutions;
- a short review of eigenvalues, eigenvectors and diagonalization
  (Lesson 3.2), placed right before linear systems, where it is first needed.

**Level of rigour.** Solution methods are derived, not just stated. The
existence and uniqueness theorem is proved in full by Picard iteration
(Unit 6). The one idea it needs beyond ANA101, uniform convergence, is
introduced in that unit. A few results are stated with explanation but proved
in later courses:

| Result | Lesson | Proved in |
|---|---|---|
| Uniqueness of the inverse Laplace transform | 4.1 | ANA303 Fourier Analysis |
| Convergence of Frobenius series | 5.3 | ANA301 Complex Analysis |
| Poincaré–Bendixson theorem | 7.4 | ANA305 Dynamical Systems and Chaos |
| Convergence of Fourier series and completeness of Sturm–Liouville eigenfunctions | 8.2, 8.3 | ANA303 Fourier Analysis, ANA402 Functional Analysis |

**After the course** you should be able to solve first-order, second-order and
linear-system equations by the standard methods, use the Laplace transform and
power series, prove that an initial-value problem has a unique solution, and
analyse equilibria of nonlinear systems. The milestone task is: classify the
equilibria of a nonlinear planar system and sketch its phase portrait.

**Optional reading.** Boyce & DiPrima, *Elementary Differential Equations and
Boundary Value Problems*; Hirsch, Smale & Devaney, *Differential Equations,
Dynamical Systems, and an Introduction to Chaos*; Tenenbaum & Pollard,
*Ordinary Differential Equations*.

## Lessons

| Lesson | Title | Status |
|---|---|---|
| **Unit 0** | **Preliminaries** | |
| 0.1 | Complex numbers and Euler's formula | Planned |
| 0.2 | What is a differential equation? Solutions, initial-value problems, direction fields | Planned |
| **Unit 1** | **First-order equations** | |
| 1.1 | Separable equations | Planned |
| 1.2 | Linear equations and integrating factors | Planned |
| 1.3 | Modelling: mixing, cooling, population growth, circuits | Planned |
| 1.4 | Exact equations | Planned |
| 1.5 | Substitutions: homogeneous and Bernoulli equations | Planned |
| 1.6 | Autonomous equations, equilibria and phase lines | Planned |
| 1.7 | Euler's method | Planned |
| **Unit 2** | **Second-order linear equations** | |
| 2.1 | Homogeneous equations: superposition, the Wronskian, fundamental sets | Planned |
| 2.2 | Constant coefficients: real, repeated and complex roots | Planned |
| 2.3 | Reduction of order | Planned |
| 2.4 | Undetermined coefficients | Planned |
| 2.5 | Variation of parameters | Planned |
| 2.6 | Mechanical and electrical vibrations: damping and resonance | Planned |
| 2.7 | Higher-order linear equations | Planned |
| **Unit 3** | **Linear systems** | |
| 3.1 | Systems of first-order equations; rewriting higher-order equations as systems | Planned |
| 3.2 | Matrix review: eigenvalues, eigenvectors, diagonalization | Planned |
| 3.3 | Constant-coefficient systems with real distinct eigenvalues | Planned |
| 3.4 | Complex eigenvalues | Planned |
| 3.5 | Repeated eigenvalues and generalized eigenvectors | Planned |
| 3.6 | The matrix exponential | Planned |
| 3.7 | Phase portraits of planar linear systems | Planned |
| 3.8 | Non-homogeneous systems | Planned |
| **Unit 4** | **The Laplace transform** | |
| 4.1 | Definition and basic transforms | Planned |
| 4.2 | Solving initial-value problems | Planned |
| 4.3 | Step functions and discontinuous forcing | Planned |
| 4.4 | Impulses and the Dirac delta | Planned |
| 4.5 | Convolution | Planned |
| **Unit 5** | **Series solutions** | |
| 5.1 | Power series solutions near an ordinary point | Planned |
| 5.2 | Regular singular points and Euler equations | Planned |
| 5.3 | The Frobenius method | Planned |
| 5.4 | Bessel's equation | Planned |
| **Unit 6** | **Existence and uniqueness** | |
| 6.1 | Lipschitz conditions and Grönwall's inequality | Planned |
| 6.2 | Picard iteration and the existence and uniqueness theorem | Planned |
| 6.3 | Continuous dependence, maximal solutions and blow-up | Planned |
| **Unit 7** | **Nonlinear systems and stability** | |
| 7.1 | Equilibria and linearization | Planned |
| 7.2 | Competing species and predator–prey models | Planned |
| 7.3 | Lyapunov functions | Planned |
| 7.4 | Periodic solutions and limit cycles | Planned |
| **Unit 8** | **Boundary-value problems** | |
| 8.1 | Two-point boundary-value problems and eigenvalue problems | Planned |
| 8.2 | Fourier series | Planned |
| 8.3 | Sturm–Liouville problems | Planned |
| 8.4 | Eigenfunction expansions and a first look at the heat equation | Planned |

Each unit will end with a **unit review** of mixed problems with solutions,
and the course ends with a **final assessment**.

## Connections to other courses

- **Uses from ANA101:** integration techniques (Unit 5 there) throughout
  Unit 1; power series (Lesson 7.6 there) in Unit 5; improper integrals
  (Lesson 5.4 there) in Unit 4.
- **Prepares for:** ANA302 Partial Differential Equations (Unit 8 and the
  heat equation preview), ANA305 Dynamical Systems and Chaos (Units 3 and 7),
  ANA304 Calculus of Variations, CMP302 Numerical Methods for Differential
  Equations (Lesson 1.7), PHY301 Classical Mechanics.
- **Overlap:** Lesson 8.2 introduces Fourier series only as far as
  boundary-value problems need them. ANA303 Fourier Analysis treats them fully.

## Open questions

1. **Figures.** Direction fields and phase portraits are central here, even
   more than in ANA101. The same decision applies as for ANA101.
2. **Computation.** Euler's method (Lesson 1.7) and phase portraits are much
   clearer with a computer. Exercises could be by hand only, or include
   optional short programs; this depends on the series-wide programming
   decision.
3. **Unit 8 placement.** Boundary-value problems could move to ANA302, making
   ANA201 shorter. Keeping them here gives ANA302 a gentler start.
