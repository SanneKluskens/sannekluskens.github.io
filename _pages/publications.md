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

<h2 class="category">{{ Publications }}</h2>
  hoi
  
{%- if site.enable_project_categories and page.display_categories %}
  {%- for category in page.display_categories %}
    <h2 class="category">{{ category }}</h2>
  
    {%- if category == Publications %}
      Publications
    {%- endif -%}
  
    {%- if category == Master's thesis %}
        Master's thesis
    {%- endif -%}
  
    {%- if category == Bachelor's thesis %}
      Bachelor's thesis
    {%- endif -%}

  {% endfor %}

{%- endif -%}
 

