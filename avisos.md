---
layout: default
title: Avisos
subtitle: Avisos
permalink: /avisos/
---

<ul>
{% for post in site.categories.avisos %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <small>({{ post.date | date: "%d/%m/%Y" }})</small>
  </li>
{% endfor %}
</ul>
