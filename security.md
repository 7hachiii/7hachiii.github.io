---
layout: default
title: Security
permalink: /security/
---

<h1>Security</h1>

{% for post in site.categories.security %}
  <p>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </p>
{% endfor %}
