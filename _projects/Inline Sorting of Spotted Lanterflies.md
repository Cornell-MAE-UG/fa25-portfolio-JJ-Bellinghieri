---
layout: project
title: Inline Separation of Spotted Lanternflies
description: Class project to design a mechanism to address the problems caused by SLF in grape harvesting
technologies: []
image: /assets/images/sorter.png

fontsize: 11pt
geometry: margin=1in
papersize: letter
pagestyle: empty
mainfont: Times New Roman
header-includes:
  - \usepackage{sectsty}
  - \sectionfont{\fontsize{14}{16}\selectfont}  # H1
  - \subsectionfont{\fontsize{12}{14}\selectfont} # H2
  - \usepackage{setspace}
  - \setstretch{1.15}

---

<div class="gallery-container">
<div class="2250-gallery">
    {% for project in site.2250 %}
      <div class="gallery-item">
        <a href="{{ 2250.url | relative_url }}">
          <img src="{{ 2250.image | relative_url }}" alt="{{ 2250.title }}" />
          <p>{{ 2250.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>