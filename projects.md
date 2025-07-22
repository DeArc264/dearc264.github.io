---
layout: default
title: "Projects"
---

<div>
  <h1><strong>Projects</strong></h1>
  <p>Some personal projects I worked on or am currently working on.</p>
</div>

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Projects" %}
{% endif %}
