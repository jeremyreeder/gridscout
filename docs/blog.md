---
layout: default
title: GridScout™ Blog
permalink: /blog/
---

This blog is dedicated to the proficient defensive use of MGRS maps, the
[GridScout™][gridscout] Google-Maps client, and other tools.

# Blog
Subscribe: <a href="feed.xml">Atom feed</a>
{% for post in site.posts %}
# [{{ post.title }}][{{ post.url }}]
{{ post.content }}
{% endfor %}


[feed]:      /feed.xml
[gridscout]: /
