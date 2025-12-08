---
layout: home
---

# Recientes

<ul class="post-list">
{% for post in site.posts limit:3 %}
  <li>
    <h3 class="post-title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p class="post-date">{% include date-spanish.html date=post.date %}</p>
  </li>
{% endfor %}
</ul>

<p style="text-align: center; margin-top: 30px;">
  <a href="/posts/" style="display: inline-block; padding: 10px 20px; background-color: #0066cc; color: white; text-decoration: none; border-radius: 5px;">Todos los posts →</a>
</p>