---
layout: default
title: Home
---

# Welcome

Welcome to my personal site. Below are recent posts on this blog:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
