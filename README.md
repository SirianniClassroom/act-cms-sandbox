ACT-CMS Development Sandbox
===========================

Repo for organizing OER development for ACT-CMS.

## Modules

Multi-part modules below organized into top-level directories in the
repository, and further broken into individual lesson subdirectories.  Each
lesson is packaged into four parts: 

- Key: Complete lesson with full author commentary in Markdown cells and filled
code cells, intended as a reference for adopting instructors;
- Async: Complete lesson with full author commentary in Markdown cells but with
redacted code cells, intended for students to read and complete asynchronously
at their own pace;
- Skeleton: Skeleton with author commentary & code cells redacted and only
lesson headings & structure preserved, intended for faculty-led instruction via
livecoding; and
- Notes: Implementation advice from the lesson author, including a discussion
of lesson timing, student challenges, common pitfalls, troubleshooting, and
other commentary intended to support adopting instructors.

Lessons are tagged according to their category, topic, focus, scope, intended
course, and depth of discussion according to the principles below.

- Category: Predominant purpose of lesson. While intersections may exist, this
tag describes the major learning outcomes of the lesson.
    * `pchem`: Focuses on physical chemistry concepts
    * `cyber`: Focuses on cyberinfrastructure skills
    * `math`: Focuses on mathematical concepts
- Topic: Specifies the conceptual topics discussed in the lesson
- Prereq: Specifies which other lesson(s) are assumed prior knowledge

#### Contents

| Category               | Module                                          | Lessons                                                                | Beta?  | Pilot?  | Deploy? |
|:----------------------:|:------------------------------------------------|:-----------------------------------------------------------------------|:------:|:-------:|:-------:|
| CI Foundations         | Python Basics                                   | Python Syntax                                                          | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Python Functions                                                       | [ ]    | [ ]     | [ ]     |
|                        | Symbolic Mathematics in SymPy                   | Symbolic Algebra                                                       | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Symbolic Calculus                                                      | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Operators in SymPy                                                     | [ ]    | [ ]     | [ ]     |
|                        | Numerical Mathematics in NumPy & SciPy          | Introduction to NumPy                                                  | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Vectors & Vector Operations                                            | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Matrices & Matrix Operations                                           | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Solving Matrix Equations                                               | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Solving Eigenvalue Problems                                            | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Numerical Calculus                                                     | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Numerical Solution to Systems of Linear Equations                      | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Numerical Solution to Differential Equations                           | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Computational Efficiency of Array Contraction Engines                  | [ ]    | [ ]     | [ ]     |
|                        | Data Analysis & Manipulation in Pandas          | Introduction to Pandas                                                 | [ ]    | [ ]     | [ ]     |
|                        |                                                 |                                                                        | [ ]    | [ ]     | [ ]     |
|                        | Data Visualization                              | Introduction to Matplotlib                                             | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Introduction to Seaborn                                                | [ ]    | [ ]     | [ ]     |
|                        | Model Fitting                                   | Linear Regression                                                      | [ ]    | [ ]     | [ ]     |
|                        |                                                 |                                                                        | [ ]    | [ ]     | [ ]     |
| Math Foundations       |                                                 |                                                                        | [ ]    | [ ]     | [ ]     |
|                        | Calculus                                        | Calculus of Scalar Functions                                           | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Vector Calculus                                                        | [ ]    | [ ]     | [ ]     |
|                        | Linear Algebra                                  | Foundational Linear Algebra                                            | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Vector Spaces                                                          | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Operators, Operator Properties, & Operator Eigenproblems               | [ ]    | [ ]     | [ ]     |
|                        | Statistics                                      | Uncertainty Analysis of Measured Data                                  | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Uncertainty Propagation in Derived Results                             | [ ]    | [ ]     | [ ]     |
|                        |                                                 |                                                                        | [ ]    | [ ]     | [ ]     |
| Quantum Mechanics (QM) | Development of Quantum Mechanics                | Blackbody Radiation                                                    | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Photoelectric Effect                                                   | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Bohr Model                                                             | [ ]    | [ ]     | [ ]     |
|                        |                                                 |                                                                        | [ ]    | [ ]     | [ ]     |
|                        | Postulates of Quantum Mechanics                 | Postulates of QM                                                       | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Introduction to QM Operators                                           | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Properties of QM Operators                                             | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Properties of Operator Eigenstates                                     | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Expectation Value, Variance, & Heisenberg Uncertainty                  | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Measurement & Wavefunction Collapse                                    | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Uncertainty Relationships                                              | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Time Evolution of Operator Eigenstates                                 | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Variation Principle                                                    | [ ]    | [ ]     | [ ]     |
|                        | Exactly Solvable Toy Systems                    | The Free Particle                                                      | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle in a 1-Dimensional Box                                        | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle in a 3-Dimensional Box                                        | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle in a 1-Dimensional Harmonic Trap                              | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle-on-a-Ring                                                     | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle-on-a-Sphere                                                   | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle in an Infinite Square Well                                    | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle in an Infinite Circular Well                                  | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Particle in an Infinite Spherical Well                                 | [ ]    | [ ]     | [ ]     |
|                        |                                                 |                                                                        | [ ]    | [ ]     | [ ]     |
|                        | Approximate Solution Methods                    | Method of Linear Variations                                            | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Nondegenerate Perturbation Theory                                      | [ ]    | [ ]     | [ ]     |
|                        | Molecular Spectroscopy                          | Free Electron Model for Absorption Spectra of Conjugated Dyes          | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Harmonic Approximation for Vibrational Spectra of Diatomic Molecules   | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Harmonic Approximation for Vibrational Spectra of Polyatomic Molecules | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Rovibrational Spectra of Diatomic Molecules                            | [ ]    | [ ]     | [ ]     |
|                        | Spectroscopic Case Studies                      | Absorption Spectra of Linear Polyenes                                  | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Vibrational Spectra of HCl/DCl                                         | [ ]    | [ ]     | [ ]     |
|                        |                                                 | Quantum Dots                                                           | [ ]    | [ ]     | [ ]     |


