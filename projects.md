---
layout: page
title: Projects
permalink: /projects/
---

{% for project in site.projects %}
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
  <p>{{ project.subtitle }}</p>
  <p>{{ project.timeline }}</p>
{% endfor %}

---

### First year engineering design course projects
[This is a portfolio we made for the course where the goal was to ooutline our personal contributions, goals, and lessons learned.](https://www.notion.so/Christine-Wei-2d9781805de080529d6bf99038639c0d?source=copy_link)

### High school projects
[See where it all started](https://uglysquid.github.io/jekyll/update/2026/04/22/hs-projects.html)