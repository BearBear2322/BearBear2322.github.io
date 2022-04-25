---
title: "Java 카테고리의 포스트"
layout: archive
permalink: categories/java
author_profile: true
---

{% assign posts = site.categories.Java %}
{% for post in posts %}
{% include archive-single.html type=page.entries.layout %}
{% endfor %}
