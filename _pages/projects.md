---
layout: default
permalink: /projects/
title: Projects
description:
nav: true
nav_order: 4
---
<!-- _pages/projects.md -->
{% assign project_name_size = site.project_page_name | size %}
{% assign project_description_size = site.project_description | size %}

{% if project_name_size > 0 or project_description_size > 0 %}

  <div class="header-bar">
    <h1>{{ site.project_page_name}}</h1>
    <h4>{{ site.project_description}}</h4>
    <p>Feel free to checkout my <a href="https://github.com/Laura05010">GitHub</a> to find the most updated list of projects.</p>
  </div>
{% endif %}


<div class="publications">
<div class="search-bar-container">
    {% include bib_search.liquid %}
</div>
{% bibliography %}
</div>
