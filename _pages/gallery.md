---
layout: page
title: gallery
permalink: /gallery/
nav: true
nav_order: 5
---

<div class="gallery-masonry">

  <div class="gallery-item">
    <img src="/assets/img/gallery/talk_tokyo.jpg" alt="CAMPUS Asia Final Symposium, Tokyo" loading="lazy">
    <div class="gallery-caption">CAMPUS Asia Plus Final Symposium · Institute of Science Tokyo, Jan 2026</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/qisk.jpg" alt="QISK 2026" loading="lazy">
    <div class="gallery-caption">2026 QISK Conference · Seoul, Feb 2026</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/talk_kaist.jpg" alt="CAMPUS Asia KAIST" loading="lazy">
    <div class="gallery-caption">2025 CAMPUS Asia Joint Research Presentation · KAIST, Aug 2025</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/bohr.jpg" alt="Niels Bohr Institute" loading="lazy">
    <div class="gallery-caption">Niels Bohr Institute · Copenhagen, Aug 2025</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/group_nelly.jpg" alt="The inQlings, NTU Singapore" loading="lazy">
    <div class="gallery-caption">The inQlings group (Prof. Nelly Ng) · NTU Singapore, 2024</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/bintan.jpg" alt="Bintan Island, Singapore" loading="lazy">
    <div class="gallery-caption">Lab trip to Bintan Island · Singapore, 2024</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/img/gallery/kaist_mit.jpg" alt="KAIST-MIT Quantum Winter School" loading="lazy">
    <div class="gallery-caption">KAIST-MIT Quantum Winter School · Daejeon, Jan 2024</div>
  </div>

</div>

<style>
  .gallery-masonry {
    columns: 3;
    column-gap: 1rem;
    margin-top: 1.5rem;
  }

  @media (max-width: 768px) {
    .gallery-masonry {
      columns: 2;
    }
  }

  @media (max-width: 480px) {
    .gallery-masonry {
      columns: 1;
    }
  }

  .gallery-item {
    break-inside: avoid;
    margin-bottom: 1rem;
    position: relative;
    overflow: hidden;
    border-radius: 6px;
    cursor: pointer;
  }

  .gallery-item img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 6px;
    transition: transform 0.3s ease, filter 0.3s ease;
  }

  .gallery-item:hover img {
    transform: scale(1.02);
    filter: brightness(0.85);
  }

  .gallery-caption {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: linear-gradient(transparent, rgba(0,0,0,0.65));
    color: #fff;
    font-size: 0.78rem;
    padding: 1.2rem 0.75rem 0.6rem;
    border-radius: 0 0 6px 6px;
    opacity: 0;
    transition: opacity 0.3s ease;
  }

  .gallery-item:hover .gallery-caption {
    opacity: 1;
  }
</style>
