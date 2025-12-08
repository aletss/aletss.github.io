---
layout: home
title: "Blog de Aletss pa' los cuates"
---

<ul class="post-list">
{% for post in site.posts limit:3 %}
  <li>
    <h3 class="post-title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
  </li>
{% endfor %}
</ul>

<p style="text-align: center; margin-top: 30px;">
  <a href="/posts/">Ver todos los posts →</a>
</p>