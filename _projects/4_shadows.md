---
layout: page
title: Classical Shadow Tomography for TFIM Phase Transitions
description: "Summer 2025"
importance: 3
category: work
---

Classical shadow tomography (Huang et al., 2020) provides an efficient protocol for estimating many properties of a quantum state from a small number of random measurements. Rather than full state tomography, shadows compress measurement outcomes into a compact classical representation from which nonlinear functionals — such as Rényi entropies — can be estimated with polynomial overhead.

This project applies classical shadows to detect the quantum phase transition in the 1D **Transverse-Field Ising Model (TFIM)**:

$$H = -J \sum_i Z_i Z_{i+1} - g \sum_i X_i$$

The Rényi-2 entanglement entropy S₂ is estimated via shadow tomography and compared against exact diagonalization across the critical point g/J = 1. The shadow estimator correctly captures the divergence in entanglement at criticality, validating the method on a well-understood benchmark.

_DTU Summer School: Scientific Methods for Quantum Information Science (5 ECTS), 2025._

**Code:** [GitHub](https://github.com/junwoojung0908/Ising_Model_Classical_shadow)

**Keywords:** Classical shadows · Rényi-2 entropy · TFIM · Phase transitions · Exact diagonalization
