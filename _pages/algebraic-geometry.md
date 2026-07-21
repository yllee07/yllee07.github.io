---
title: Algebraic Geometry
permalink: /portfolio/algebraic-geometry/
---

Here you will find my writings on algebraic geometry.

{% assign items = site.portfolio | where: "tags", "algebraic-geometry" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
