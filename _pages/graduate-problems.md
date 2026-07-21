---
title: Graduate Problems
permalink: /portfolio/graduate-problems/
---

Here you will find my solutions to graduate-level problems (qualifying exams, Qiu Chengtong competitions, etc.).

{% assign items = site.portfolio | where: "tags", "graduate-problems" %}
{% for item in items %}
- [{{ item.title }}]({{ item.url }}) — {{ item.excerpt }}
{% endfor %}
