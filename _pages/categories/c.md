---
title: "C 카테고리의 포스트"
layout: archive
permalink: categories/c
author_profile: true
---

{% assign posts = site.categories.C %}
{% for post in posts %}
{% include archive-single.html type=page.entries.layout %}
{% endfor %}
