---
layout: page
title: Writings
---

This includes informal writing, blog posts, notes, or commentary.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%Y" }})</span>
    </li>
  {% endfor %}
</ul>
