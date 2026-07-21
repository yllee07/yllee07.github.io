---
title: Arithmetic Geometry
permalink: /portfolio/arithmetic-geometry/
---

Here you will find my writings on arithmetic geometry.

{% assign items = site.portfolio | where: "tags", "arithmetic-geometry" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
