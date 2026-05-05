---
layout: default
title: JJ Bellinghieri - Portfolio
permalink: /projects/
---

<h2>Categories</h2>
<ul>
  <li><a href="/projects/mech/">Intro Mech Design Projects</a></li>
</ul>

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