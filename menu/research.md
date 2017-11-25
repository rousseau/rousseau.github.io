---
layout: page
title: Research
---
My research area is image analysis for understanding early brain development.

{% for project in site.research %}
<a href="{{ site.baseurl }}{{ project.url }}">
{{ project.title }}: {{ project.description }}
</a>
{% endfor %}