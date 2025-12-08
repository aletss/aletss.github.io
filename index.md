---
layout: home
title: "Welcome to My Blog"
---

# Blog Posts

Below are the latest posts:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date_to_string }}</small>
{% endfor %}