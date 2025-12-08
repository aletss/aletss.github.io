---
layout: home
title: "Blog de Aletss pa' los cuates"
---

# Blog Posts

Below are the latest posts:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date_to_string }}</small>
    {% if post.dedicatoria %}
      <br><em>{{ post.dedicatoria }}</em>
    {% endif %}
    
{% endfor %}