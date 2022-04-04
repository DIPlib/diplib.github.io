---
layout: default
---

# Change logs

{% assign posts = site.changelogs | sort:'date' | reverse %}

<ul>
{% for post in posts %}
 {% if post.url != "/changelogs/index.html" %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
 {% endif %}
{% endfor %}
</ul>
