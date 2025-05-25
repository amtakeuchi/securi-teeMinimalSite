---
layout: single
title: "Projects"
permalink: /projects/
---

<ul>
  {% for project in site.data.projects %}
    <li style="margin-bottom: 2rem;">
      <img src="{{ project.image }}" alt="{{ project.title }}" style="max-width:600px; width:100%; height:auto; border-radius:6px; margin-bottom: 1rem;">
      <h3>{{ project.title }}</h3>
      <p>{{ project.description }}</p>
      <a href="{{ project.url }}" target="_blank" style="color:#33D6FF; font-weight:bold;">View Project</a>
    </li>
  {% endfor %}
</ul>

---


