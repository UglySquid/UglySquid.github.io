---
layout: page
title: Projects
permalink: /projects/
---
{% for project in site.projects %}
<div style="margin-bottom: 2rem;">
    <p style="margin: 0; font-size: 0.85rem; color: #888;">{{ project.timeline }}</p>
    <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="{{ project.url }}" style="color: black;">{{ project.title }}</a></h3>
    <p style="margin: 0;">
        <span style="font-size: 0.8rem; background: #fdf0e8; color: #d4621a; padding: 2px 8px; border-radius: 10px; font-weight: 600;">
            Designed for: {{ project.subtitle }}
        </span>
    </p>
</div>

{% endfor %}

<div style="margin-bottom: 2rem;">
    <p style="margin: 0; font-size: 0.85rem; color: #888;">2021 - 2025</p>
    <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="https://uglysquid.github.io/jekyll/update/2026/04/22/hs-projects.html" style="color: black;">High school projects</a></h3>
    <p style="margin: 0;">
        <span style="font-size: 0.8rem; background: #fdf0e8; color: #d4621a; padding: 2px 8px; border-radius: 10px; font-weight: 600;">
            Designed for: Various purposes (FRC team, Fun, etc.)
        </span>
    </p>
</div>

<hr style="border: none; height: 1px; background: linear-gradient(to right, transparent, #ccc, transparent); margin: 2rem 0;">

<div style="
  display: inline-flex;
  align-items: center;
  gap: 10px;
  padding: 8px 14px;
  background: #F9FAFB;
  border-radius: 8px;
  border: 0.5px solid #D1D5DB;
  margin: 0.5rem 0 1.25rem;
">
  <svg width="16" height="16" viewBox="0 0 16 16" fill="none" style="flex-shrink: 0;">
    <path d="M8 1.5L14.5 13H1.5L8 1.5Z" stroke="#6B7280" stroke-width="1.4" fill="none"/>
    <line x1="8" y1="6" x2="8" y2="9.5" stroke="#6B7280" stroke-width="1.4" stroke-linecap="round"/>
    <circle cx="8" cy="11.2" r="0.7" fill="#6B7280"/>
  </svg>
  <span style="font-size: 13px; color: #374151;">
    The following links open in an external page (Notion, Google Drive)
  </span>
</div>

<div style="margin-bottom: 2rem;">
    <p style="margin: 0; font-size: 0.85rem; color: #888;"> September 2025 - April 2026</p>
    <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="https://www.notion.so/Christine-Wei-2d9781805de080529d6bf99038639c0d?source=copy_link" style="color: black;" target="_blank">First year engineering design course projects (Notion portfolio)</a></h3>
    <p style="margin: 0;">
        <span style="font-size: 0.8rem; background: #e8f0fb; color: #4a90d9; padding: 2px 8px; border-radius: 10px; font-weight: 600;">
            Designed for: 1P13 Engineering Design Course
        </span>
    </p>
</div>

<div style="margin-bottom: 2rem;">
    <p style="margin: 0; font-size: 0.85rem; color: #888;">2021 - 2025</p>
    <h3 style="margin: 0.2rem 0 0.2rem 0;"><a href="https://drive.google.com/drive/folders/1qn9GRRLwHr-_M_EnJgjU5jKH3yMzlNcP?usp=drive_link" style="color: black;" target="_blank">Archive of very old projects</a></h3>
    <p style="margin: 0;">
        <span style="font-size: 0.8rem; background: #e8f0fb; color: #4a90d9; padding: 2px 8px; border-radius: 10px; font-weight: 600;">
            Designed for: Learning and fun
        </span>
    </p>
</div>