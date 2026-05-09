---
layout: default
title: 160 Minute Dance With History
---

<h1 class="post-title">160 Minute Dance With History</h1>
<p class="post-excerpt">From iceberg to abyss — a minute by minute account of the night of April 14th to 15th, 1912.</p>

<div class="post-list">
{% for article in site.articles %}
  {% if article.series == "160 Minute Dance With History" %}
  <article class="post-item">
    <a href="{{ article.url }}" class="post-title"><h2>{{ article.title }}</h2></a>
    <p class="post-meta">{{ article.date | date: "%B %Y" }}</p>
  </article>
  {% endif %}
{% endfor %}
</div>
