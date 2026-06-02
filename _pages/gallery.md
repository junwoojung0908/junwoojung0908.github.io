---
layout: page
title: gallery
permalink: /gallery/
nav: true
nav_order: 5
---

<div class="gallery">

  <h2 class="year">2023</h2>

  <div class="gallery-item">
    <img src="/assets/img/gallery/GTC.jpg" alt="KSA-Ellen Young School Exchange" loading="lazy">
    <p class="gallery-caption">KSA × Ellen Young School Short-term Exchange · Hong Kong, Jan 2023</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/graduation.jpg" alt="KSA Graduation" loading="lazy">
    <p class="gallery-caption">KSA Graduation · Feb 2023</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/QCL.jpg" alt="QCL Group Photo" loading="lazy">
    <p class="gallery-caption">Quantum Computing Lab (Prof. Jaewook Ahn) · KAIST, 2023</p>
  </div>

  <h2 class="year">2024</h2>

  <div class="gallery-item">
    <img src="/assets/img/gallery/kaist_mit.jpg" alt="KAIST-MIT Quantum Winter School" loading="lazy">
    <p class="gallery-caption">KAIST-MIT Quantum Winter School · Daejeon, Jan 2024</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/group_nelly.jpg" alt="The inQlings, NTU" loading="lazy">
    <p class="gallery-caption">The inQlings group (Prof. Nelly Ng) · NTU Singapore, 2024</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/bintan.jpg" alt="Bintan Island" loading="lazy">
    <p class="gallery-caption">Lab trip to Bintan Island · Singapore, 2024</p>
  </div>

  <h2 class="year">2025</h2>

  <div class="gallery-item">
    <img src="/assets/img/gallery/talk_kaist.jpg" alt="CAMPUS Asia KAIST" loading="lazy">
    <p class="gallery-caption">2025 CAMPUS Asia Joint Research Presentation · KAIST, Aug 2025</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/bohr.jpg" alt="Niels Bohr Institute" loading="lazy">
    <p class="gallery-caption">Niels Bohr Institute · Copenhagen, Aug 2025</p>
  </div>

  <h2 class="year">2026</h2>

  <div class="gallery-item">
    <img src="/assets/img/gallery/talk_tokyo.jpg" alt="CAMPUS Asia Tokyo" loading="lazy">
    <p class="gallery-caption">CAMPUS Asia Plus Final Symposium · Institute of Science Tokyo, Jan 2026</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/qisk.jpg" alt="QISK 2026" loading="lazy">
    <p class="gallery-caption">2026 QISK Conference · Seoul, Feb 2026</p>
  </div>

</div>

<style>
  .gallery {
    margin-top: 1.5rem;
  }

  /* Year marker — same as publications: large, light Fraunces numeral.
     color-mix matches publications' light@0.5-over-bg while keeping the
     group divider border crisp (opacity would fade the border too). */
  .gallery h2.year {
    font-family: var(--font-display);
    font-optical-sizing: auto;
    font-size: 2.6rem;
    font-weight: 400;
    line-height: 1;
    letter-spacing: -0.01em;
    color: color-mix(
      in srgb,
      var(--global-text-color-light) 50%,
      var(--global-bg-color)
    );
    margin: 0 0 1.2rem;
    padding-top: 2.6rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .gallery h2.year:first-of-type {
    padding-top: 0.5rem;
    border-top: 0;
  }

  /* Single-column photos — constrained width, hairline border, no shadow */
  .gallery-item {
    margin-bottom: 2rem;
  }
  .gallery-item img {
    width: 100%;
    max-width: 600px;
    height: auto;
    border-radius: 6px;
    border: 1px solid var(--global-divider-color);
    display: block;
  }

  .gallery-caption {
    margin-top: 0.5rem;
    font-family: var(--font-mono);
    font-size: var(--font-size-label);
    letter-spacing: 0.02em;
    color: var(--global-text-color-light);
    line-height: 1.5;
  }
</style>
