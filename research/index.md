---
layout: page
title: "Research"
group: navigation
description: "List of the projects that I have worked on or currently working on"

---
{% include JB/setup %}

<div class="row">
<div class="span6">
<h3>ONGOING PROJECTS</h3>
<br />
<ul class="nav">
 {% assign pages_list = site.pages %}
 {% assign group = 'projects-ongoing' %}
 {% include custom/pages_list_with_desc %}
</ul>

</div>
<div class="span6">

<h3>COMPLETED PROJECTS</h3>
<br />
<ul class="nav">
 {% assign pages_list = site.pages %}
 {% assign group = 'projects-complete' %}
 {% include custom/pages_list_with_desc %}
</ul>

</div>
</div>