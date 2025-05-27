---
layout: single
title: "Projects"
permalink: /projects/
---

<div class="projects-grid">
  {% for project in site.data.projects %}
    <div class="project-card">
      <img src="{{ project.image }}" alt="{{ project.title }}">
      <h3>{{ project.title }}</h3>
      <p>{{ project.description }}</p>
      <a href="{{ project.url }}" class="project-link">View Project</a>
    </div>
  {% endfor %}
</div>
