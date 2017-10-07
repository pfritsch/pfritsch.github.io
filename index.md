---
title: Titre de la page de bienvenue
description: Description
authors:
  - @pfritsch
  - @eToileGraphic
---

{{site.description}}

<h1>{{ site.title }}</h1>

<ul>
{% for post in posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
