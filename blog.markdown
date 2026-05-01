---
layout: page
title: Blog
permalink: /blog/
---

Short updates about building OpenSurf.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}