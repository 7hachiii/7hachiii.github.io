---
layout: default
title: Math
permalink: /math/
---

<h1>Math</h1>

{% for post in site.categories.math %}
  <p>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </p>
{% endfor %}
