---
layout: default
---

# Change logs

{% assign posts = site.changelogs| sort:'date' %}

<ul>
{% for post in posts %}
 {% if page.url != note.url %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
 {% endif %}
{% endfor %}
</ul>
