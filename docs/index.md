---
layout: default
title: "Home"
---

# Welcome to NTNU LRA

This is the homepage for NTNU LRA's official website.

{% for post in paginator.posts %}
  ## {{ post.title }}
  *{{ post.date | date_to_string }}*

  {{ post.content }}
{% endfor %}
