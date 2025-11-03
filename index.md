---
layout: home
title: Website
---

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>


Welcome to my personal site and blog!
