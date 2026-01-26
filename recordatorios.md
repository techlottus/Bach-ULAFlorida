---
layout: default
title: Recordatorios
subtitle: Recordatorios
permalink: /recordatorios/
---

<ul>
{% for post in site.categories.recordatorios %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <small>({{ post.date | date: "%d/%m/%Y" }})</small>
  </li>
{% endfor %}
</ul>
