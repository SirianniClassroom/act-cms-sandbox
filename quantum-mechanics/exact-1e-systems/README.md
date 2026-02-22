Exactly Solvable One Particle Systems
=====================================

This module applies quantum mechanics to several exactly solvable systems,
involving a single particle subject to the following potentials:

- Zero potential (a.k.a. the free particle)
- Infinite square well (a.k.a. the particle-in-a-box, PiB)
- Infinite circular well
- Infinite spherical well
- Quadratic (a.k.a. the quantum harmonic oscillator)
- Particle on a Ring (a.k.a. the 2D rigid rotator, 2D RR)
- Particle on a Sphere (a.k.a. the 3D rigid rotator, 3D RR)
- Coulomb (a.k.a. the hydrogen atom)

While several of these potentials represent toy systems which are reasonable
spectroscopic models, the discussion in this module is limited to the form and
properties of the system's Hamiltonian eigenstates, including their expected
positions, momenta, energies, and probability distributions; treatment of their
spectroscopic implications is left to another module.

## Module Contents

Lessons in this module are grouped according to the toy system under consideration
and ranked according to their level of mathematical rigor:
- Level 1 (:atom:): Purely wave-equation based discussion, no operators employed
- Level 2 (:warning:): Operators employed, no discussion of Hilbert spaces or operator properties
- Level 3 (:radioactive:): Discussion relies on Dirac notation, properties of Hilbert spaces and their generating operators

| Potential               | System              | Lesson Directory     | Description | Level |
|:-----------------------:|
| Zero                    | Free Particle       | `free-particle-L2`   | Explores complex-valued solutions to the free particle wave equation            | :warning:     |
|                         |                     | `free-particle-L3`   | Explores properties of Hamiltonian eigenstates in momentum space                | :radioactive: |
| Infinite Square Well    | 1D PiB              | `particle-1d-box-L2` | Explores 1-dimensional PiB eigenstates & properties w/ Heisenberg               | :warning:     |
|                         |                     | `particle-1d-box-L3` | Explores 1D PiB eigenstates as basis for representing arbitrary function        | :radioactive: |
|                         | 3D PiB              | `particle-3d-box-L2` | Solves 3D PiB with given direct product wavefunction, explores properties       | :warning:     |
|                         | _N_D PiB            | `particle-Nd-box-L2` | Explores solution to infinite square well wave equation in arbitrary dimensions | :warning:     |
| Infinite Circular Well  | Circular Well       |                      |                                                                                 |               |
| Infinite Spherical Well | Spherical Well      |                      |                                                                                 |               |
| Quadratic               | Harmonic Oscillator |                      |                                                                                 |               |
| Angular Square Well     | 2D Rigid Rotator    |                      |                                                                                 |               | 
|                         | 3D Rigid Rotator    |                      |                                                                                 |               | 
| Coulombic               | Hydrogen Atom       |                      |                                                                                 |               |

For further details on lesson learning outcomes, prerequisites, etc., please
refer to the module contents.

