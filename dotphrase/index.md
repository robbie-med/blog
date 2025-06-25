---
layout: default
title: Dotphrases
---

# 📋 Dotphrases

Browse all clinical dotphrases below:

<ul>
  {% assign sorted = site.dotphrases | sort: 'title' %}
  {% for page in sorted %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
