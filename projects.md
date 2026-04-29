---
layout: page
title: Projects
permalink: /projects/
---

{% for project in site.projects %}
<div style="margin-bottom: 2rem;">
  <p style="margin: 0; font-size: 0.85rem; color: #888;">{{ project.timeline }}</p>
  <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="{{ project.url }}">{{ project.title }}</a></h3>
  <p style="margin: 0;">{{ project.subtitle }}</p>
</div>
{% endfor %}

<hr>

### First year engineering design course projects
[This is a portfolio we made for the course where the goal was to ooutline our personal contributions, goals, and lessons learned.](https://www.notion.so/Christine-Wei-2d9781805de080529d6bf99038639c0d?source=copy_link)

### High school projects
[See where it all started](https://uglysquid.github.io/jekyll/update/2026/04/22/hs-projects.html)