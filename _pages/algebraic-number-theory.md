---
title: Algebraic Number Theory
permalink: /portfolio/algebraic-number-theory/
---

Here you will find my writings on algebraic number theory.

{% assign items = site.portfolio | where: "tags", "algebraic-number-theory" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
