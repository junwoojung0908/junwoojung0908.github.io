---
layout: page
permalink: /publications/
title: publications & talks
nav: true
nav_order: 3
---

## publications

Also on [Google Scholar](https://scholar.google.com/citations?user=uUQhFGAAAAAJ) →

<div class="talks talks--pub">

  <h2 class="year">2026</h2>

  <div class="talk">
    <div class="talk-title">Decay versus Dephasing in Rydberg Analog Optimization: Exchange Rate, Mechanism, and Schedule Design</div>
    <div class="talk-meta">
      <span class="talk-venue">S. Kim and <span class="me">Junwoo Jung</span> &mdash; <a href="https://arxiv.org/abs/2608.29858">arXiv:2608.29858</a></span>
    </div>
    <details class="talk-abs-toggle">
      <summary>abstract</summary>
      <p class="talk-abstract">Numerical studies of noisy Rydberg-atom optimization almost universally compress decoherence into a single scalar, silently pricing spontaneous decay (Γ) and dephasing (γ) alike. We treat the two as independent axes, mapping a quantum-annealing heuristic for unit-disk maximum independent set on 20 random N = 10 graphs across the (Γ, γ) plane, with the annealing time re-optimized at every point. The mean approximation ratio does collapse onto one scalar, but onto u = κΓ + γ with κ = 8.05 ± 0.5 (stat) ± 1.1 (syst); the isotropic Γ + γ fails by a factor of 30 in residual. First-order perturbation theory reproduces κ from noiseless propagation alone and gives the mechanism: the objective is diagonal in the basis of the dephasing operator, so dephasing cannot change the answer once the drive is off, and a single driven atom already has κ ≃ 8.5. The exchange rate is thus a property of the protocol as much as of the platform: the ramp-down fraction moves it between 2.3 and 16.3. At a fixed schedule it is stable across system sizes, interaction strengths, and estimators. Because the whole cost model is noiseless, a schedule can be tuned to a device's channel mixture without any noisy simulation: jointly tuning the drive ramp-down and the sweep's detuning ramp recovers about a third of the Markovian damage at no hardware cost, and the ramp the noise-aware objective selects is not the one noiseless optimization would choose. Per unit rate decay is eightfold the dearer channel, but the measured T₁ enters weighted by its branching ratio to the ground state (b ≈ 0.4 for the calibrated device), which leaves the two Lindblad channels comparably costly at a present-day operating point. One-parameter noise models remain serviceable, provided the parameter is u.</p>
    </details>
  </div>

  <div class="talk">
    <div class="talk-title">Shots-to-Approximate-Solution Scaling in Neutral-Atom Quantum Optimization</div>
    <div class="talk-meta">
      <span class="talk-venue"><span class="me">Junwoo Jung</span> and J. Ahn &mdash; <a href="https://arxiv.org/abs/2608.12858">arXiv:2608.12858</a></span>
    </div>
    <details class="talk-abs-toggle">
      <summary>abstract</summary>
      <p class="talk-abstract">Whether neutral-atom quantum optimization protocols exhibit genuine concentration toward low-energy solution structure remains an open question. Here, we introduce a shots-to-approximate-solution metric, STS(r), where r denotes the approximation ratio, and evaluate it using postprocessed outputs modeled by a degeneracy-weighted shell distribution governed by a single effective parameter, β, that quantifies concentration toward near-optimal independent sets. To extract the genuine concentration effect in the quantum data, we apply identical postprocessing to both experimental bitstrings and randomly generated bitstrings with matched excitation density, thereby constructing an excitation-matched random baseline. Experiments on programmable Rydberg-atom arrays with system sizes up to 125 sites show that quantum annealing consistently exceeds the random baseline, demonstrating enhanced concentration toward low-energy solution structure beyond what can be attributed solely to excitation density. The results further reveal two distinct target-dependent regimes. For near-exact targets with r ≈ 1, the required shot count grows exponentially with system size and is reduced at the same exponential level by quantum annealing within the shell-model description. By contrast, for relaxed targets, the shot cost becomes effectively constant, and the corresponding quantum enhancement diminishes, with the classical postprocessing heuristic alone reaching the target in order-unity attempts. Together, these results establish an operational method for quantifying quantum optimization performance and clarify the regimes under which quantum approaches can yield practical benefits.</p>
    </details>
  </div>

  <div class="talk">
    <div class="talk-title">Quantum-Enhanced Deterministic Inference of k-Independent Set Instances on Neutral Atom Arrays</div>
    <div class="talk-meta">
      <span class="talk-venue">J. Park, <span class="me">Junwoo Jung</span>, and J. Ahn &mdash; <a href="https://arxiv.org/abs/2602.05432">arXiv:2602.05432</a></span>
    </div>
    <details class="talk-abs-toggle">
      <summary>abstract</summary>
      <p class="talk-abstract">Noisy quantum annealing experiments on Rydberg atom arrays produce measurement outcomes that deviate from ideal distributions, complicating performance evaluation. To enable a data-driven benchmarking methodology for quantum devices that accounts for both solution quality and the classical computational cost of inference from noisy measurements, we introduce deterministic error mitigation (DEM), a shot-level inference procedure informed by experimentally characterized noise. We demonstrate this approach using the decision version of the k-independent set problem. Within a Hamming-shell framework, the DEM candidate volume is governed by the binary entropy of the bit-flip error rate, yielding an entropy-controlled classical postprocessing cost. Using experimental measurement data, DEM reduces postprocessing overhead relative to classical inference baselines. Numerical simulations and experimental results from neutral atom devices validate the predicted scaling with system size and error rate. These scalings indicate that one hour of classical computation on an Intel i9 processor corresponds to neutral atom experiments with up to N = 250&ndash;450 atoms at effective error rates, enabling a direct, cost-based comparison between noisy quantum experiments and classical algorithms.</p>
    </details>
  </div>

  <h2 class="year">2024</h2>

  <div class="talk">
    <div class="talk-title">Rydberg-atom graphs for quadratic unconstrained binary optimization problems</div>
    <div class="talk-meta">
      <span class="talk-venue">A. Byun, <span class="me">Junwoo Jung</span>, K. Kim, M. Kim, S. Jeong, H. Jeong, and J. Ahn &mdash; <em>Advanced Quantum Technologies</em>, 2024 &mdash; <a href="https://doi.org/10.1002/qute.202300398">DOI</a></span>
    </div>
    <details class="talk-abs-toggle">
      <summary>abstract</summary>
      <p class="talk-abstract">There is a growing interest in harnessing the potential of the Rydberg-atom system to address complex combinatorial optimization challenges. Here an experimental demonstration of how the quadratic unconstrained binary optimization (QUBO) problem can be effectively addressed using Rydberg-atom graphs is presented. The Rydberg-atom graphs are configurations of neutral atoms organized into mathematical graphs, facilitated by programmable optical tweezers, and designed to exhibit many-body ground states that correspond to the maximum independent set (MIS) of their respective graphs. Four elementary Rydberg-atom subgraph components are developed, not only to eliminate the need of local control but also to be robust against interatomic distance errors, while serving as the building blocks sufficient for formulating generic QUBO graphs. To validate the feasibility of the approach, a series of Rydberg-atom experiments selected to demonstrate proof-of-concept operations of these building blocks are conducted. These experiments illustrate how these components can be used to programmatically encode the QUBO problems to Rydberg-atom graphs and, by measuring their many-body ground states, how their QUBO solutions are determined subsequently.</p>
    </details>
  </div>

</div>

---

## talks

<div class="talks talks--talk">

  <h2 class="year">2026</h2>

  <div class="talk">
    <div class="talk-title">Deterministically Error-Mitigated Performance in Rydberg Quantum Computing for Maximum Independent Set</div>
    <div class="talk-meta">
      <span class="talk-type badge">Poster</span>
      <span class="talk-venue">2026 QISK Conference · Seoul, South Korea · 2026.02</span>
    </div>
  </div>

  <div class="talk">
    <div class="talk-title">Efficiency of Quantum Computing</div>
    <div class="talk-meta">
      <span class="talk-type badge">Oral</span>
      <span class="talk-venue">CAMPUS Asia Program, Institute of Science Tokyo · Tokyo, Japan · 2026.01</span>
    </div>
    <div class="talk-photo">
      <img src="/assets/img/talk_tokyo.jpg" alt="Talk at Institute of Science Tokyo" />
    </div>
  </div>

  <h2 class="year">2025</h2>

  <div class="talk">
    <div class="talk-title">Resource Theory of Quantum Computing</div>
    <div class="talk-meta">
      <span class="talk-type badge">Oral</span>
      <span class="talk-venue">CAMPUS Asia Program, KAIST · Daejeon, South Korea · 2025.08</span>
      <span class="talk-award">★ Second Place Presentation Award</span>
    </div>
    <div class="talk-photo">
      <img src="/assets/img/talk_kaist.jpg" alt="Talk at KAIST" />
    </div>
  </div>

</div>
