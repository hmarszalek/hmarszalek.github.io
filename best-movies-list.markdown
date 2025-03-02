---
title: Best Movies of All Time
---

# Best 100 movies of all time
In a random order.

<a href="index">Main page</a>

{% for movie in site.movies %}
## <a href="{{ movie.url }}">{{ movie.title }}</a>
<p><strong>Directed by: </strong>{{ movie.director }}</p>
{% endfor %}

{% for movie in site.movies %}
<h2><a href="{{ movie.url }}">{{ movie.title }}</a></h2>
<p><strong>Directed by: </strong>{{ movie.director }}</p>
{% endfor %}