---
title: Best Movies List
---

# Best 25 movies of all time chronologically

<a href="index">Main page</a>

{% for movie in site.movies %}
<h2><a href="{{ movie.url }}">{{ movie.title }}</a></h2>
<p><strong>Directed by: </strong>{{ movie.director }}</p>
<p><strong>Release date: </strong>{{ movie.date | date: "%-d %B %Y" }}</p>
<p>{{ movie.desription }}</p>
{% endfor %}