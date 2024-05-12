---
title: Blog
date: 2024-01-02
layout: default
tags: [primary]
---
{% for post in collections.blog %}
- [{{ post.data.title }}]({{ post.url | url }})
{% endfor %}