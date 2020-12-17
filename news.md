---
layout: default
title: "News"
---

# News

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a>
  ({{ post.date | date: "%d %B %Y" }})</li>
{% endfor %}
</ul>
