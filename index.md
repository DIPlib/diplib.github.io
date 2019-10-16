The DIPlib website is currently at [diplib.org](http://www.diplib.org).

The documentation for DIPlib 3.0 is at [diplib-docs](https://diplib.github.io/diplib-docs/).

---

<h2>News</h2>

<ul>
{% for post in site.posts limit:3 %}
  <li><a href="{{ post.url }}">{{ post.title }}</a>
  ({{ post.date | date: "%d %B %Y" }})</li>
{% endfor %}
</ul>

[All news](./news.html)
