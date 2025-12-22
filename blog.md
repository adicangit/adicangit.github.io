---
layout: default
title: Blog
---

# Blog

{% if site.posts.size > 0 %}
<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">— {{ post.date | date: "%B %d, %Y" }}</span>
    {% if post.description %}
    <p>{{ post.description }}</p>
    {% endif %}
  </li>
  {% endfor %}
</ul>
{% else %}
<p>No posts yet. Check back soon!</p>
{% endif %}
