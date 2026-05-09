---
layout: default
title: Hull 401
---

<h1 class="post-title">Hull 401</h1>
<p class="post-excerpt">The ship, the build, the yard — the story of how she was made in Belfast.</p>

<div class="post-list">
{% for article in site.articles %}
  {% if article.series == "Hull 401" %}
  <article class="post-item">
    <a href="{{ article.url }}" class="post-title"><h2>{{ article.title }}</h2></a>
    <p class="post-meta">{{ article.date | date: "%B %Y" }}</p>
  </article>
  {% endif %}
{% endfor %}
</div>
