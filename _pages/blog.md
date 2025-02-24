---
layout: default
title: "Blog de Destinos"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small> ({{ post.date | date: "%d-%m-%Y" }})</small>
    </li>
  {% endfor %}
</ul>