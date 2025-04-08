---
layout: home
title: Home
---

# Welcome to My Blog

This is a personal blog where I share my thoughts, projects, and experiences.

## Recent Posts

{% for post in site.posts limit:5 %}

- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endfor %}
