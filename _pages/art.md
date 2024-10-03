---
layout: default
title: Art
permalink: /art/
nav: true
nav_order: 2
horizontal: false
---
<!-- pages/projects.md -->
<div class="projects">

{% assign art_name_size = site.art_name | size %}
{% assign art_description_size = site.art_description | size %}

{% if art_name_size > 0 or art_description_size > 0 %}

  <div class="header-bar">
    <h1>{{ site.art_name}}</h1>
    <h4>{{ site.art_description}}</h4>
  </div>
  {% endif %}



  <!-- Display all projects in a single column -->
  <div class="container">
    <div class="row row-cols-1"> <!-- Ensuring single column display -->
    {% assign sorted_projects = site.projects | sort: "importance" %}
    {% for project in sorted_projects %}
      {% include art.liquid %}
    {% endfor %}
    </div>
  </div>

</div>

