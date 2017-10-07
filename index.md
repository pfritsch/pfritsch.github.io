---
title: Titre de la page de bienvenue
description: Description
authors:
  - @pfritsch
  - @eToileGraphic
---

# {{ site.title }}

{{site.description}}

<h1>{{ page.title }}</h1>

{% for post in posts %}
    {{ post.title }}
{% endfor %}
