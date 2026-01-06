---
layout: default
title: Inicio
---

# Bienvenido

Artículos recientes:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

