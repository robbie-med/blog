---
layout: default
title: High Yield Notes
---

# 🚀 High Yield Clinical Notes

<ul>
  {% assign sorted = site.high_yield | sort: 'title' %}
  {% for page in sorted %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
