---
layout: page
permalink: /publications/
title: publications
description: ""
nav: true
nav_order: 1
display_categories: [Publications, Master's thesis, Bachelor's thesis]
horizontal: false
---
<!-- _pages/publications.md -->
<div class="publications">

{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  <!-- Generate cards for each project -->
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}


