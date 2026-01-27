---
layout: default
title: Recordatorios
subtitle: Recordatorios
permalink: /recordatorios/
---

<div class="posts-grid">
{% for post in site.categories.avisos %}
  <article class="post-card">
    <h3 class="post-title">
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </h3>

    <div class="post-meta">
      {{ post.date | date: "%d/%m/%Y" }}
    </div>

    <p class="post-excerpt">
      {{ post.excerpt | strip_html | truncate: 220 }}
    </p>

    <a class="post-btn" href="{{ site.baseurl }}{{ post.url }}">Leer más</a>
  </article>
{% endfor %}
</div>