---
layout: page
title: "Research"
group: navigation
order: 1
description: "List of the projects that I have worked on or currently working on"

---
{% include JB/setup %}

<div class="row">
<div class="span6">
<h3>Projects Completed During Ph.D.</h3>
<br />
<ul class="nav">
 {% assign pages_list = site.pages %}
 {% assign group = 'projects-phd' %}
 {% include custom/pages_list_with_desc %}
</ul>

</div>
<div class="span6">

<h3>Projects Completed During M.S.</h3>
<br />
<ul class="nav">
 {% assign pages_list = site.pages %}
 {% assign group = 'projects-ms' %}
 {% include custom/pages_list_with_desc %}
</ul>

</div>
</div>