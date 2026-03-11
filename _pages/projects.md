---
layout: default
title: Andre Ababio - Portfolio
permalink: /projects/
---

This page highlights selected engineering projects and technical work completed during my studies in Civil Engineering at Cornell University.

My work focuses primarily on structural engineering and transportation systems, including design analysis, modeling, and infrastructure planning.
<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
