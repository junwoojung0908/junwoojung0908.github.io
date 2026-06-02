---
layout: page
title: projects
permalink: /projects/
description:
nav: true
nav_order: 2
horizontal: false
---

<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="project-list">
    {% for project in sorted_projects %}
      {% include projects.liquid index=forloop.index %}
    {% endfor %}
  </div>
</div>
