---
layout: page
title: Blog
permalink: /blog/
description: Notes on dataflow architectures, compilers, and research.
nav: true
nav_order: 4
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h3>
        <a class="post-title" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
      <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p>
      {% if post.description %}
        <p>{{ post.description }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>
