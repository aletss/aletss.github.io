---
layout: page
title: Todos los posts
---

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <h3 class="post-title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
  </li>
{% endfor %}
</ul>