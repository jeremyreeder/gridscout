---
layout: default
title: GridScout™ Journal
permalink: /journal/
redirect_from: /blog/
---

# GridScout™ Journal
Here's what's going on in the manly arts, from the [GridScout™][gridscout] team.

Subscribe: [Atom feed][feed]

{% for post in site.posts %}
<div class="post" markdown="1">
# [{{ post.title }}]({{ post.url }})
<div class="post-metadata">{{ post.date | date: "%Y-%m-%d" }} — by {{ post.author }}</div>
{{ post.content }}
<div class="post-metadata">© {{ post.date | date: "%Y" }} {{ post.author }} &amp; gridscout.net </div>
</div>
{% endfor %}

Subscribe to GridScout™ Journal: [Atom feed][feed]


[feed]:      /feed.xml
[gridscout]: /
