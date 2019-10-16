---
layout: page
title: "News"
---

<h1>News</h1>

{% for post in site.posts %}
  <a href="{{ post.url }}">
  <h3>{{ post.title }}</h3>
  <p class="blogdate">{{ post.date | date: "%d %B %Y" }}</p>
  </a>
{% endfor %}
