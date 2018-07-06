---
layout: default
title: GridScout™ Blog
permalink: /blog/
---

# GridScout™ Blog
This blog is dedicated to the proficient defensive use of MGRS maps, the
[GridScout™][gridscout] Google-Maps client, and other tools well suited to the
goals of GridScout™.

Subscribe: <a href="feed.xml">Atom feed</a>

{% for post in site.posts %}
# [{{ post.title }}]({{ post.url }})
[{{ post.date | date: "%Y-%m-%d" }}]
{{ post.content }}
{% endfor %}

Subscribe to GridScout™ Blog: <a href="feed.xml">Atom feed</a>


[feed]:      /feed.xml
[gridscout]: /
