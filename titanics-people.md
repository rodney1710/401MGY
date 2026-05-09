---
layout: default
title: Titanic's People
---

<h1 class="post-title">Titanic's People</h1>
<p class="post-excerpt">Passengers, crew, survivors — one person per article, properly researched.</p>

<div class="post-list">
{% for article in site.articles %}
  {% if article.series == "Titanic's People" %}
  <article class="post-item">
    <a href="{{ article.url }}" class="post-title"><h2>{{ article.title }}</h2></a>
    <p class="post-meta">{{ article.date | date: "%B %Y" }}</p>
  </article>
  {% endif %}
{% endfor %}
</div>
