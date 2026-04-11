---
layout: page
title: gallery
permalink: /gallery/
nav: true
nav_order: 5
---

<div class="gallery-grid">

  <div class="gallery-item">
    <img src="/assets/img/gallery/qisk.jpg" alt="QISK 2026" loading="lazy">
    <p class="gallery-caption">2026 QISK Conference · Seoul, Feb 2026</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/talk_tokyo.jpg" alt="CAMPUS Asia Tokyo" loading="lazy">
    <p class="gallery-caption">CAMPUS Asia Plus Final Symposium · Institute of Science Tokyo, Jan 2026</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/talk_kaist.jpg" alt="CAMPUS Asia KAIST" loading="lazy">
    <p class="gallery-caption">2025 CAMPUS Asia Joint Research Presentation · KAIST, Aug 2025</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/bohr.jpg" alt="Niels Bohr Institute" loading="lazy">
    <p class="gallery-caption">Niels Bohr Institute · Copenhagen, Aug 2025</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/group_nelly.jpg" alt="The inQlings, NTU" loading="lazy">
    <p class="gallery-caption">The inQlings group (Prof. Nelly Ng) · NTU Singapore, 2024</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/bintan.jpg" alt="Bintan Island" loading="lazy">
    <p class="gallery-caption">Lab trip to Bintan Island · Singapore, 2024</p>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/kaist_mit.jpg" alt="KAIST-MIT Quantum Winter School" loading="lazy">
    <p class="gallery-caption">KAIST-MIT Quantum Winter School · Daejeon, Jan 2024</p>
  </div>

</div>

<style>
  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.2rem;
    margin-top: 1.5rem;
  }

  @media (max-width: 768px) {
    .gallery-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }

  @media (max-width: 480px) {
    .gallery-grid {
      grid-template-columns: 1fr;
    }
  }

  .gallery-item {
    display: flex;
    flex-direction: column;
  }

  .gallery-item img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 6px;
    border: 1px solid var(--global-divider-color);
    transition: transform 0.25s ease;
    display: block;
  }

  .gallery-item:hover img {
    transform: scale(1.02);
  }

  .gallery-caption {
    margin-top: 0.45rem;
    font-size: 0.78rem;
    color: var(--global-text-color-light);
    line-height: 1.4;
  }
</style>
