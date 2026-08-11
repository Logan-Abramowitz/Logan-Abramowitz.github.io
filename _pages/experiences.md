---
layout: default
title: <Logan Abramowitz> - Experiences
permalink: /experiences/
---

<div class="gallery-container">
<div class="project-gallery">
    {% for experience in site.experiences reversed%}
      <div class="gallery-item">
        <a href="{{ experience.url | relative_url }}">
          <img src="{{ experience.image | relative_url }}" alt="{{ experience.title }}" />
          <p>{{experience.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>