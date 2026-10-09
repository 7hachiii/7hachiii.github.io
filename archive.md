---
layout: default
title: Archive
permalink: /archive/
---

<h1>Archive</h1>

{% for post in site.categories.archive %}
  <p>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </p>
{% endfor %}
