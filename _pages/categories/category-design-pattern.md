---
title: "Design Pattern"
layout: archive
permalink: categories/design-pattern
author_profile: true
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories['design-pattern'] %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %} 