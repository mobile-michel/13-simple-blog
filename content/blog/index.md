---
title: Blog
description: This blog is about photography.
layout: default
date: 2024-01-03
override:tags: ["primary"]
---
{% for post in collections.blog %}
- [{{ post.data.title }}]( /blog/{{ post.data.title | slugify | url }}) published on {{ post.data.date | date: '%d  %b %Y' }} by {{ post.data.author }}
{% endfor %}