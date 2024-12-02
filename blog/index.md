---
layout: page
title: "Blog"
permalink: /blog/
---

# Welcome to My Blog

This is where I'll share my latest posts.

	<h1>{{ page.title }}</h1>
	<ul class="posts">

	  {% for post in site.posts %}
	    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}
	</ul>

