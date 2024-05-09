---
title: Posts
permalink: /posts/
layout: archive
author_profile: true
read_time: false
show_date: false
share: false
related: true
---
<ul>
 {% for post in site.posts %}
 	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
 {% endfor %}
</ul>
