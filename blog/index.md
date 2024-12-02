---
layout: default
title: "Blog"
permalink: /blog/
---

# Welcome to My Blog

This is where I'll share my latest posts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - 
      <small>{{ post.date | date_to_string }}</small>
    </li>
  {% endfor %}
</ul>

