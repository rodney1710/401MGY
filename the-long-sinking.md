---
layout: default
title: The Long Sinking
---

<h1 class="post-title">The Long Sinking</h1>
<p class="post-excerpt">Mysteries, controversies, unanswered questions — the information failures that changed everything.</p>

<div class="post-list">
{% for article in site.articles %}
  {% if article.series == "The Long Sinking" %}
  <article class="post-item">
    <a href="{{ article.url }}" class="post-title"><h2>{{ article.title }}</h2></a>
    <p class="post-meta">{{ article.date | date: "%B %Y" }}</p>
  </article>
  {% endif %}
{% endfor %}
</div>
