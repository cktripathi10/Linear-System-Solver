# Linear-System-Solver
In this assignment, I will implement the Gaussian elimination method, a foundational algorithm for solving systems of linear equations.

Linear algebra is fundamental to machine learning, serving as the basis for numerous algorithms. Gaussian elimination, while not the most advanced method used today, is a classical and essential technique for solving systems of linear equations. It provides valuable insights into the core principles of linear algebra and lays the groundwork for more advanced numerical methods.

# Why should you care?
- **Foundational Skills**: Strengthen our understanding of key linear algebra concepts.
- **Programming Practice**: Enhances our coding skills by implementing a classical mathematical algorithm.
- **Historical Significance**: Gaussian elimination, though not the most cutting-edge method today, is historically significant and provides a solid starting point for understanding the evolution of linear algebra techniques.

# Outline
- [ 1 - Introduction ](#1)
  - [ 1.1 How to complete this assignment](#1.1)
  - [ 1.2 Gaussian Elimination Algorithm](#1.2)
- [ 2 - Necessary imports](#2)
- [ 3 - Auxiliary functions](#3)
  - [ 3.1 - Function swap rows](#3.1)
  - [ 3.2 - Finding the first non-zero value in a column starting from a specific value](#3.2)
  - [ 3.3 - Find the first non zero element for any row](#3.3)
  - [ 3.4 Moving one row to the bottom](#3.4)
  - [ 3.5 - Constructing the Augmented Matrix](#3.5)
- [ 4 - Row echelon form](#4)
  - [ 4.1 - Row Echelon Form](#4.1)
  - [ 4.2 - A worked example ](#4.2)
    - [ Exercise 1](#ex01)
- [ 5 - Back substitution](#5)
  - [ Exercise 2](#ex02)
- [ 6 - The Gaussian Elimination](#6)
  - [ 6.1 - Bringing it all together](#6.1)
    - [ Exercise 3](#ex03)
- [ 7 - Test with any system of equations!](#7)
