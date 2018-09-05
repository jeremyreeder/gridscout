---
layout: default
title: GridScout™ Blog
permalink: /blog/
---

# GridScout™ Blog
This blog is dedicated to the proficient defensive use of MGRS maps, the
[GridScout™][gridscout] Google-Maps client, and other tools well suited to the
goals of GridScout™.

Subscribe: [Atom feed][feed]

{% for post in site.posts %}
<div class="post">
# [{{ post.title }}]({{ post.url }})
<div class="post-metadata">{{ post.date | date: "%Y-%m-%d" }} — by {{ post.author }}</div>
{{ post.content }}
</div>
{% endfor %}

Subscribe to GridScout™ Blog: [Atom feed][feed]


[feed]:      /feed.xml
[gridscout]: /
