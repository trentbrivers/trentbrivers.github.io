---
layout: default
title: Home
---

# Welcome

Track the progress on my IoT Sensor project here:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
