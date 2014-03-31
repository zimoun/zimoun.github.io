---
layout: blog
title: Archives
section: Past

feed: atom.xml
keywords: Numerical Analysis, Stuffs, Blog, Research, Academia
---

Archives
========

This is the complete archive of posts from _[my blog](/blog/)_
in reverse chronological order.

{% for post in site.categories.blog %}
<div class="section list">
  <h1>{{ post.date | date_to_string }}</h1>
  <p class="line">
  <a class="title" href="{{ post.url }}">{{ post.title }}</a>
  </p>
</div>
{% endfor %}
