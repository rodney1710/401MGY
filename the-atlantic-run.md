---
layout: default
title: The Atlantic Run
---

<h1 class="post-title">The Atlantic Run</h1>
<p class="post-excerpt">The route, the rivals, the race — the world of North Atlantic shipping in 1912.</p>

<div class="post-list">
{% for article in site.articles %}
  {% if article.series == "The Atlantic Run" %}
  <article class="post-item">
    <a href="{{ article.url }}" class="post-title"><h2>{{ article.title }}</h2></a>
    <p class="post-meta">{{ article.date | date: "%B %Y" }}</p>
  </article>
  {% endif %}
{% endfor %}
</div>
