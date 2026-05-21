---
layout: page
title: research
permalink: /research/
description:
nav: true
nav_order: 2
horizontal: false
---

## publications

Also on [Google Scholar](https://scholar.google.com/citations?user=uUQhFGAAAAAJ) →

**Shots-to-Approximate-Solution Scaling in Neutral-Atom Quantum Optimization**  
Junwoo Jung and J. Ahn · _submitted_, 2026

**Deterministically Error-Mitigated Performance in Rydberg Quantum Computing for the Maximum Independent Set Problem**  
J. Park, Junwoo Jung, and J. Ahn · _arXiv preprint_, 2026 · [arXiv:2602.05432](https://arxiv.org/abs/2602.05432)

**Rydberg-atom graphs for quadratic unconstrained binary optimization problems**  
A. Byun, Junwoo Jung, K. Kim, M. Kim, S. Jeong, H. Jeong, and J. Ahn · _Advanced Quantum Technologies_, 2024 · [DOI](https://doi.org/10.1002/qute.202300398)

---

## projects

<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
