---
layout: default
title: Inicio
---

<div class="prose">
  <h1>Bienvenido</h1>
  <p>Artículos recientes:</p>
</div>

<div class="grid">
{% for post in site.posts %}
  <div class="card">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    {% if post.excerpt %}
      <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
    {% else %}
      <p>—</p>
    {% endif %}
    <div class="meta">{{ post.date | date: "%d %B %Y" }}</div>
  </div>
{% endfor %}
</div>

