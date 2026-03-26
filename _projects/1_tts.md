---
layout: page
title: Approximation-Dependent Shots-to-Solution Scaling
description: STS(r) framework for neutral-atom quantum optimization on QuEra Aquila
importance: 1
category: work
---

Developing an approximation-ratio-resolved shots-to-solution framework, STS(_r_), for hybrid neutral-atom optimization on QuEra's Aquila platform. Postprocessed outputs are modeled by a degeneracy-weighted shell distribution governed by a single effective quality parameter β̃.

To isolate genuine quantum structural exploitation from trivial excitation density effects, we introduce an excitation-matched random baseline β̃_rand(_p_\_exc). Adiabatic annealing consistently exceeds this baseline (Δβ̃_ann > 0) across all system sizes _N_ ∈ [30, 125], confirming genuine structural exploitation. The measured advantage Δβ̃_ann = 0.23–0.40 translates into two distinct scaling regimes: exponential shots-to-solution advantage for near-exact targets (_r_ → 1), vanishing for relaxed targets (_r_ ≪ 1).

**Keywords:** QuEra Aquila · STS(r) · MIS · Rydberg annealing · Excitation-matched baseline
