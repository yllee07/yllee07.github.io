---
title: Category Theory
permalink: /portfolio/category-theory/
---

Here you will find my writings on category theory.

{% assign items = site.portfolio | where: "tags", "category-theory" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
