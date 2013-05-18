---
layout: page
title: "Projects"
group: navigation
description: "List of the projects that I have worked on or currently working on"

---
{% include JB/setup %}

<ul class="nav">
 {% assign pages_list = site.pages %}
 {% assign group = 'projects' %}
 {% include JB/pages_list %}
</ul>