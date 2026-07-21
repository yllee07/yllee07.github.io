---
title: Geometric Analysis
permalink: /portfolio/geometric-analysis/
---

Here you will find my writings on geometric analysis.

{% assign items = site.portfolio | where: "tags", "geometric-analysis" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
