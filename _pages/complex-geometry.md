---
title: Complex Geometry
permalink: /portfolio/complex-geometry/
---

Here you will find my writings on complex geometry.

{% assign items = site.portfolio | where: "tags", "complex-geometry" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
