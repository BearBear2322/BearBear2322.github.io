---
title: "Python 카테고리의 포스트"
layout: archive
permalink: categories/python
author_profile: true
---

{% assign posts = site.categories.Python %}
{% for post in posts %}
{% include archive-single.html type=page.entries.layout %}
{% endfor %}
