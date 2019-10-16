The DIPlib website is currently at [diplib.org](http://www.diplib.org).

The documentation for DIPlib 3.0 is at [diplib-docs](https://diplib.github.io/diplib-docs/).

---

<h2>News</h2>

{% for post in site.posts limit:3 %}
  <a href="{{ post.url }}">
  <h3>{{ post.title }}</h3>
  <p class="blogdate">{{ post.date | date: "%d %B %Y" }}</p>
  <div>{{ post.content | truncatehtml | truncatewords: 60 }}</div>
  </a>
{% endfor %}

[All news](./news.html)
