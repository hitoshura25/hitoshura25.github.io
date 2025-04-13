---
layout: default
title: Home
---

## Projects

{% for project in site.projects %}
<div class="project-card">
  <h3>{{ project.title }}</h3>
  <p>{{ project.description }}</p>
  <div class="technologies">
    {% for tech in project.technologies %}
    <span class="tech-tag">{{ tech }}</span>
    {% endfor %}
  </div>
  
  <div class="project-links">
    <a href="{{ project.url }}" class="button">Learn More</a>
    {% if project.github %}
    <a href="{{ project.github }}" class="button" target="_blank" rel="noopener noreferrer">GitHub</a>
    {% endif %}
  </div>
</div>
{% endfor %}
