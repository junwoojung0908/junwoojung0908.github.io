---
layout: page
title: Combinatorial Optimization on Rydberg Atom Arrays
description: >
  End-to-end study of neutral-atom quantum optimization — from QUBO graph construction
  to error mitigation and approximation-resolved performance benchmarking.
importance: 1
category: work
---

Neutral-atom quantum processors, such as those built on Rydberg-blockade physics, provide a natural hardware graph for solving combinatorial optimization problems. This project spans three interconnected threads, all carried out in Prof. Jaewook Ahn's group at KAIST.

---

### QUBO Mapping via Rydberg Graphs

Investigated how QUBO (Quadratic Unconstrained Binary Optimization) problems can be encoded into Rydberg-atom graphs and contributed to optimizing atom arrangements under no-local-detuning hardware constraints.

**Published:** _Advanced Quantum Technologies_, 2024. DOI: [10.1002/qute.202300398](https://doi.org/10.1002/qute.202300398)

---

### Deterministic Error Mitigation for MIS

Developed a DEM protocol using a physically informed binomial Hamming-shell model to evaluate Rydberg MIS experiments on Pasqal Fresnel hardware. Derived an entropy-controlled processing-cost scaling (2<sup>N H₂(p)</sup>) as a rigorous classical brute-force baseline, and identified a quantum–classical crossover around N ≈ 13.

**Preprint:** arXiv:[2602.05432](https://arxiv.org/abs/2602.05432)

---

### Approximation-Dependent Performance Benchmarking

Developing an approximation-ratio-resolved shots-to-solution framework, STS(_r_), for hybrid neutral-atom optimization on QuEra Aquila. Post-processed outputs are modeled by a degeneracy-weighted Hamming-shell distribution governed by a single effective quality parameter β̃. Adiabatic annealing consistently exceeds an excitation-matched random baseline across system sizes N ∈ [30, 125], with measured advantage Δβ̃ = 0.23–0.40. This yields two distinct scaling regimes: exponential shots-to-solution advantage for near-exact targets (r → 1), vanishing for relaxed targets (r ≪ 1).

**Status:** In preparation

---

**Keywords:** Rydberg atoms · MIS · QUBO · Error mitigation · Hamming shells · STS(r) · QuEra Aquila · Pasqal Fresnel
