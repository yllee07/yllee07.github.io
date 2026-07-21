---
title: Partial Differential Equations
permalink: /portfolio/pde/
---

Here you will find my writings on PDEs.

{% assign items = site.portfolio | where: "tags", "pde" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
