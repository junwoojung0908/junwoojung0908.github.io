---
layout: page
title: research
permalink: /projects/
description:
nav: true
nav_order: 2
horizontal: false
---

For a full list of publications, see my [Google Scholar](https://scholar.google.com/citations?user=uUQhFGAAAAAJ) profile.

---

<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
