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
    <div class="talk-title">Shots-to-Approximate-Solution Scaling in Neutral-Atom Quantum Optimization</div>
    <div class="talk-meta">
      <span class="talk-venue">Junwoo Jung and J. Ahn &mdash; <em>submitted</em></span>
    </div>
  </div>

  <div class="talk">
    <div class="talk-title">Deterministically Error-Mitigated Performance in Rydberg Quantum Computing for the Maximum Independent Set Problem</div>
    <div class="talk-meta">
      <span class="talk-venue">J. Park, Junwoo Jung, and J. Ahn &mdash; <a href="https://arxiv.org/abs/2602.05432">arXiv:2602.05432</a></span>
    </div>
  </div>

  <h2 class="year">2024</h2>

  <div class="talk">
    <div class="talk-title">Rydberg-atom graphs for quadratic unconstrained binary optimization problems</div>
    <div class="talk-meta">
      <span class="talk-venue">A. Byun, Junwoo Jung, K. Kim, M. Kim, S. Jeong, H. Jeong, and J. Ahn &mdash; <em>Advanced Quantum Technologies</em>, 2024 &mdash; <a href="https://doi.org/10.1002/qute.202300398">DOI</a></span>
    </div>
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
      <span class="talk-award">🏅 Second Place Presentation Award</span>
    </div>
    <div class="talk-photo">
      <img src="/assets/img/talk_kaist.jpg" alt="Talk at KAIST" />
    </div>
  </div>

</div>

<style>
  .talks {
    margin-top: 1.5rem;
  }

  /* Year marker — large, light, editorial numerals */
  .talks h2.year {
    font-family: var(--font-display);
    font-optical-sizing: auto;
    font-size: 2.6rem;
    font-weight: 400;
    line-height: 1;
    letter-spacing: -0.01em;
    color: var(--global-text-color-light);
    opacity: 0.5;
    border-bottom: 0;
    padding: 0;
    margin: 2.6rem 0 0.9rem;
  }
  .talks h2.year:first-of-type {
    margin-top: 0.5rem;
  }

  /* Entry — hairline separated, no box */
  .talk {
    padding: 1.15rem 0;
    margin: 0;
    border-bottom: 1px solid var(--global-divider-color);
  }

  .talk-title {
    font-family: var(--font-display);
    font-optical-sizing: auto;
    font-size: 1.18rem;
    font-weight: 600;
    line-height: 1.3;
    color: var(--global-text-color);
    margin-bottom: 0.4rem;
  }

  .talk-meta {
    font-size: 0.9rem;
    color: var(--global-text-color-light);
    display: flex;
    align-items: baseline;
    gap: 0.7rem;
    flex-wrap: wrap;
    margin: 0;
  }

  /* Meta line (publications + talks) — monospace micro-label, muted */
  .talk-venue {
    font-family: var(--font-mono);
    font-size: 0.74rem;
    letter-spacing: 0.03em;
    color: var(--global-text-color-light);
  }
  .talk-venue a {
    color: var(--global-text-color);
    transition: color 0.25s ease;
  }
  .talk-venue a:hover {
    color: var(--global-theme-color);
  }

  /* POSTER / ORAL — mono tag, thin outline, no rust pill */
  .talk-type.badge {
    background: transparent !important;
    box-shadow: none !important;
    color: var(--global-text-color-light) !important;
    border: 1px solid var(--global-divider-color);
    border-radius: 0;
    font-family: var(--font-mono);
    font-size: 0.62rem;
    font-weight: 400;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 0.12rem 0.45rem;
  }

  /* Award — muted micro-label, not rust */
  .talk-award {
    font-family: var(--font-mono);
    font-size: 0.72rem;
    letter-spacing: 0.04em;
    font-weight: 400;
    color: var(--global-text-color-light);
  }

  .talk-photo {
    margin-top: 0.8rem;
  }
  .talk-photo img {
    width: 100%;
    max-width: 480px;
    border-radius: 6px;
    border: 1px solid var(--global-divider-color);
    display: block;
  }
</style>
