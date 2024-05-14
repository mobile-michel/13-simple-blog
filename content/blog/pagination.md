---
title: Blog
description: This blog is about photography.
layout: paginate
date: 2024-01-03
eleventyExcludeFromCollections: true
pagination:
  data: collections.blog
  size: 1
permalink: "/blog/{{ pagination.items[0].data.title | slugify }}/index.html"
---
<h3>{{ pagination.items[0].data.title }}</h3>
<p>{{ pagination.items[0].content }}</p>
