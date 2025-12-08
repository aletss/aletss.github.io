---
layout: home
title: "Blog de Aletss pa' los cuates"
---

# Blog Posts

Últimas entradas:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}){% if post.subtitle %}<small> (<em>{{ post.subtitle }}</em>) </small>{% endif %}<small> {{ post.date | date_to_string }}</small>
    
{% endfor %}