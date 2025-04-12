---
title: "Python Programming"
layout: archive
permalink: /categories/python-basic
author_profile: true
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories['python-basic'] %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}