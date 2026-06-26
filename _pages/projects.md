---
layout: page
title: Projects
permalink: /projects/
description: A growing collection of my research projects
nav: true
nav_order: 2
display_categories: [GW phenomenology, Astrophysics]
horizontal: true
hero_image_light: projects-light.jpg
hero_image_dark: projects-dark.jpg
hero_pos: center 50%
hero_credit_light: "Photo: <a href='https://commons.wikimedia.org/wiki/File:LIGO_Hanford_aerial_05.jpg' target='_blank' rel='noopener'>LIGO Laboratory</a> · public domain"
hero_credit_dark: "Image: <a href='https://commons.wikimedia.org/wiki/File:Black_hole_-_Messier_87.jpg' target='_blank' rel='noopener'>Event Horizon Telescope</a> · CC BY 4.0"
---

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
