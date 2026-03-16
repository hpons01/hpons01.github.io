---
layout: default
title: Writeups
permalink: /writeups/
---

# Writeups

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
