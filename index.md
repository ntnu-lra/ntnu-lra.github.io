---
layout: default
title: "Home"
---

# Legged Robots for the Arctic and beyond lab

This is the homepage for NTNU's LRA lab

{% for post in paginator.posts %}
  ## {{ post.title }}
  *{{ post.date | date_to_string }}*

  {{ post.content }}
{% endfor %}
