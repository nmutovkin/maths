# ALG101 Linear Algebra I

Linear equations, matrices, vectors and linear maps in ℝⁿ, up to eigenvalues,
orthogonality and the spectral theorem for symmetric matrices. First course of
the [algebra track](../../curriculum/03-algebra.md), and an entry course of
the whole series alongside [ANA101](../ANA101/README.md).

## About this course

**Prerequisites.** Secondary-school algebra. No calculus is needed, so
ALG101 can be studied before, after or alongside ANA101. Like the rest of the
series, the course assumes you can read and follow proofs.

**Level of rigour.** Every result about ℝⁿ is proved. The course stays
concrete: vectors are columns of real numbers and every linear map is given by
a matrix. Abstract vector spaces over arbitrary fields are left to ALG201.
One result is used without proof:

| Result | Used in | Proved in |
|---|---|---|
| Fundamental theorem of algebra: every non-constant polynomial has a complex root | Lessons 7.5, 8.6 | ANA301 Complex Analysis |

**Computation and theory together.** Each lesson has two kinds of exercise:
hand computations on small matrices (2 × 2 to 4 × 4), and short proofs. Both
are needed: the computations build the intuition that the proofs make precise.

**After the course** you should be able to solve linear systems, compute with
matrices, find bases and dimensions, compute determinants and eigenvalues,
diagonalize matrices, and solve least-squares problems, and to prove the
theorems behind these methods. The milestone task is: orthogonally
diagonalize a symmetric 3 × 3 matrix and use the result to compute a high
power of it.

**Optional reading.** Strang, *Introduction to Linear Algebra*; Lay, *Linear
Algebra and Its Applications*; Anton, *Elementary Linear Algebra*.

## Lessons

| Lesson | Title | Status |
|---|---|---|
| **Unit 1** | **Systems of linear equations** | |
| 1.1 | Linear equations and their geometry | Planned |
| 1.2 | Gaussian elimination and row echelon form | Planned |
| 1.3 | Reduced row echelon form; describing solution sets | Planned |
| 1.4 | Applications: networks, chemical equations, polynomial interpolation | Planned |
| **Unit 2** | **Matrix algebra** | |
| 2.1 | Matrix operations | Planned |
| 2.2 | Matrix multiplication: properties and the transpose | Planned |
| 2.3 | Inverse matrices | Planned |
| 2.4 | Elementary matrices; computing inverses; the invertible matrix theorem | Planned |
| 2.5 | Block matrices and LU factorization | Planned |
| **Unit 3** | **Vectors in ℝⁿ** | |
| 3.1 | Vectors and linear combinations | Planned |
| 3.2 | Dot product, length and angle; the Cauchy–Schwarz inequality | Planned |
| 3.3 | Lines and planes in ℝ³; the cross product | Planned |
| 3.4 | Projections and distances | Planned |
| **Unit 4** | **Subspaces of ℝⁿ** | |
| 4.1 | Subspaces and span | Planned |
| 4.2 | Linear independence | Planned |
| 4.3 | Basis and dimension | Planned |
| 4.4 | Column space, row space, null space and rank | Planned |
| 4.5 | Coordinates with respect to a basis | Planned |
| **Unit 5** | **Linear maps** | |
| 5.1 | Linear maps ℝⁿ → ℝᵐ and their matrices | Planned |
| 5.2 | Geometry of linear maps of the plane: rotations, reflections, shears, projections | Planned |
| 5.3 | Kernel and image; injective and surjective maps | Planned |
| 5.4 | The rank–nullity theorem | Planned |
| 5.5 | Change of basis and similar matrices | Planned |
| **Unit 6** | **Determinants** | |
| 6.1 | Determinants of 2 × 2 and 3 × 3 matrices; area and volume | Planned |
| 6.2 | The general determinant: permutations and cofactor expansion | Planned |
| 6.3 | Properties: row operations, products, transposes, invertibility | Planned |
| 6.4 | Cramer's rule and the adjugate | Planned |
| **Unit 7** | **Eigenvalues and eigenvectors** | |
| 7.1 | Eigenvalues, eigenvectors and eigenspaces | Planned |
| 7.2 | The characteristic polynomial | Planned |
| 7.3 | Diagonalization | Planned |
| 7.4 | Applications: matrix powers, recurrences, Markov chains | Planned |
| 7.5 | Complex numbers and complex eigenvalues | Planned |
| **Unit 8** | **Orthogonality** | |
| 8.1 | Orthogonal sets and orthonormal bases | Planned |
| 8.2 | Orthogonal projection onto a subspace | Planned |
| 8.3 | Gram–Schmidt and QR factorization | Planned |
| 8.4 | Least squares | Planned |
| 8.5 | Orthogonal matrices | Planned |
| 8.6 | Symmetric matrices and the spectral theorem | Planned |
| 8.7 | Quadratic forms and conic sections | Planned |

Each unit will end with a **unit review** of mixed problems with solutions,
and the course ends with a **final assessment**.

## Connections to other courses

- **Prepares for:** ALG201 Linear Algebra II and ALG202 Groups and Rings
  (directly); ANA102 Calculus II (Jacobian matrices, change of variables);
  ANA201 ODEs (linear systems); GEO201 Geometry (isometries); CMP201
  Numerical Analysis and CMP301 Numerical Linear Algebra; PRB302 Stochastic
  Processes (Markov chains).
- **Overlap with ANA201:** ANA201 has its own lessons on complex numbers
  (0.1) and on eigenvalues (3.2). Since ANA201 requires ALG101, both could
  become short reviews pointing back to Lessons 7.5 and Unit 7 here.
- **Revisited in ALG201:** the same ideas over arbitrary fields and in
  abstract vector spaces, plus Jordan form and the general spectral theorem.

## Open questions

1. **Complex numbers.** Lesson 7.5 introduces them so that the spectral
   theorem (8.6) can be proved properly: its proof needs the fact that a real
   symmetric matrix has a real eigenvalue, which is shown by working over ℂ.
   The alternative is to work only over ℝ and postpone complex eigenvalues to
   ALG201, with a less complete proof of the spectral theorem here.
2. **Applications.** Lessons 1.4 and 7.4 pick a few applications. Others
   could be added or swapped in: computer graphics, Google's PageRank,
   cryptography (Hill cipher), linear regression.
3. **Computation.** Row reduction of larger matrices is tedious by hand.
   Exercises could stay by hand, or include optional short programs; this
   depends on the series-wide programming decision.
