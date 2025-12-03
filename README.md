# Theoretical Foundations

![Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Theoretical%20Physics-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Overview
This repository serves as documentation for a rigorous 3-year self-study program designed to bridge the gap between high school curriculum and advanced theoretical physics.

Seeking a rigorous logic absent in standard curricula, I self-studied **Tom M. Apostol's *Calculus*** (Vol. 1) to master derivation from first principles. This mathematical foundation enabled me to progress through MIT OpenCourseWare syllabi for Multivariable Calculus, Linear Algebra, and Quantum Mechanics.

**Objective:** To build the mathematical maturity required to understand Quantum Field Theory and engineer quantum simulations.

---

## 🗺️ Curriculum Roadmap

The study was conducted in two distinct phases: **Mathematics** (The Toolset) and **Quantum Mechanics** (The Application).

| Phase | Subject | Source Material | Key Output |
| :--- | :--- | :--- | :--- |
| **I** | **Rigorous Calculus** | *Calculus Vol. 1* (Apostol) | Derivation of Limits & Integrals |
| **I** | **Multi-Variable Calc** | MIT 18.02 (Denis Auroux) | Vector Fields, Flux, Stokes' Theorem |
| **I** | **Linear Algebra** | MIT 18.06 (Gilbert Strang) | Vector Spaces, Eigenvalues |
| **I** | **Differential Eq.** | MIT 18.03 (Arthur Mattuck) | Second-order ODEs, Fourier Series |
| **II** | **Quantum Physics I** | MIT 8.04 (Allan Adams) | Schrödinger Eq, 1-3D Potentials, Spin Theory |
| **II** | **Quantum Physics II** | MIT 8.05 (Barton Zwiebach) | Spin-1/2 Systems, Quantum Dynamics |

---

## 📂 Repository Structure

### `/01_Calculus_Foundations`
* **Focus:** Axiomatic construction of Single Variable Calculus.
* **Content:**
    * [Foundational_Derivations.pdf](./01_Calculus_Foundations/Foundational_Derivations.pdf): Rigorous proofs of the **Mean Value Theorem** and **Fundamental Theorem of Calculus**, derived from first principles using Apostol's axiomatic framework (Chapters 1-10).

### `/02_Multivariable_Calculus_MIT_1802`
* **Focus:** Vector Analysis and Field Theory.
* **Content:**
    * [Vector_Calculus_Notes.pdf](./02_Multivariable_Calculus_MIT_1802/Vector_Calculus_Notes.pdf): Comprehensive notes covering **Gradient, Divergence, and Curl**. Includes derivations of **Green's Theorem** and **Stokes' Theorem** (essential prerequisites for Electromagnetism).

### `/03_Linear_Algebra_MIT_1806`
* **Focus:** Matrix Factorization and Spectral Theory.
* **Content:**
    * [Linear_Algebra_Notes.pdf](./03_Linear_Algebra_MIT_1806/Linear_Algebra_Notes.pdf): Detailed notes on **Singular Value Decomposition (SVD)** and the **Spectral Theorem** for Symmetric Matrices. Includes exploration of **Positive Definite Matrices** and their role in optimization.

### `/04_Differential_Equations_MIT_1803`
* **Focus:** Dynamic Systems and Transform Methods.
* **Content:**
    * [Differential_Equations_Notes.pdf](./04_Differential_Equations_MIT_1803/Differential_Equations_Notes.pdf): Analysis of **Non-Homogeneous Linear ODEs** using Variation of Parameters. Covers **Laplace Transforms**, **Convolution Integrals**, and **Delta Functions** for impulse response.

### `/05_Quantum_Mechanics_MIT_804_805`
* **Focus:** Wave mechanics, Operator formalism, and Entanglement.
* **Content:**
    * [Quantum_Physics_1_Notes.pdf](./05_Quantum_Mechanics_MIT_804_805/Quantum_Physics_1_Notes.pdf): Synthesized notes covering the **Schrödinger Equation**, **1D Potentials** (Infinite Well), and the **Harmonic Oscillator** (Algebraic & Analytic methods). Includes analysis of Scattering and Tunneling phenomena.
    * [Quantum_Physics_2_Notes.pdf](./05_Quantum_Mechanics_MIT_804_805/Quantum_Physics_2_Notes.pdf): Advanced notes on **General Formalism** (Dirac Notation), **Spin-1/2 Systems** (Pauli Matrices), and **Angular Momentum**. Detailed derivation of **Bell's Inequalities** and Quantum Entanglement dynamics.
    * [Selected_Hard_Problems.pdf](./05_Quantum_Mechanics_MIT_804_805/Selected_Hard_Problems.pdf): Solutions to high-difficulty problem sets (e.g., Stern-Gerlach experiments).

---

## 🔬 Applied Project: Quantum Entanglement Simulation
The theoretical knowledge gathered in this repository was applied to build a functional **Quantum Entanglement Visualization Engine** using Python and Qiskit.

* **Project Goal:** To visualize the collapse of wave functions and the dynamics of decoherence.
* **Verification:** The simulation logic was reviewed and verified by Prof. Unlu.
* **Link to Project Repo:** [INSERT LINK TO YOUR SIMULATION REPO HERE]

---

## 📜 License
These notes are open-sourced under the MIT License to encourage every interested person regardless of age to pursue rigorous theoretical study.
