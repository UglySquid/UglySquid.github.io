---
layout: page
title: Projects
permalink: /projects/
---
{% for project in site.projects %}
<div style="margin-bottom: 2rem;">
    <p style="margin: 0; font-size: 0.85rem; color: #888;">{{ project.timeline }}</p>
    <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="{{ project.url }}" style="color: black; text-decoration: none;">{{ project.title }}</a></h3>
    <p style="margin: 0;">
        <span style="font-size: 0.8rem; background: #fdf0e8; color: #d4621a; padding: 2px 8px; border-radius: 10px; font-weight: 600;">
            Designed for: {{ project.subtitle }}
        </span>
    </p>
</div>

{% endfor %}

<hr style="margin-bottom: 2rem;">

<div style="margin-bottom: 2rem;">
    <p style="margin: 0; font-size: 0.85rem; color: #888;"> September 2025 - April 2026</p>
    <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="https://www.notion.so/Christine-Wei-2d9781805de080529d6bf99038639c0d?source=copy_link" style="color: black; text-decoration: none;">First year engineering design course projects</a></h3>
    <p style="margin: 0;">
        <span style="font-size: 0.8rem; background: #e8f0fb; color: #4a90d9; padding: 2px 8px; border-radius: 10px; font-weight: 600;">
            Designed for: 1P13 Engineering Design Course
        </span>
    </p>
</div>


<div style="margin-bottom: 2rem;">
    <p style="margin: 0; font-size: 0.85rem; color: #888;">2021 - 2025</p>
    <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="https://uglysquid.github.io/jekyll/update/2026/04/22/hs-projects.html" style="color: black; text-decoration: none;">High school projects</a></h3>
    <p style="margin: 0;">
        <span style="font-size: 0.8rem; background: #e8f0fb; color: #4a90d9; padding: 2px 8px; border-radius: 10px; font-weight: 600;">
            Designed for: Various purposes
        </span>
    </p>
</div>