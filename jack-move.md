---
layout: page
title: Jack Move
description: Cyberpunk. ATB. RPG.
permalink: /jack-move/
categories: [home, games, first]
image: /assets/icons/jack_move.gif
---

## A cyberpunk JRPG. Currently WIP.

{% for post in site.categories.jack-move %}
<div class="post {% if site.animated %}animated fade-in-down{% endif %}">
  <a href="{{ post.url | prepend: site.baseurl }}" class="post-link">
  <p class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</p>
  <h3 class="post-title">{{ post.title }}</h3>
  <p class="post-summary">{{ post.summary }}</p>
  <article class="post-content">
	  {{ post.content }}
	</article>
</a>
</div>
{% endfor %}

