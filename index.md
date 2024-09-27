---
layout: default
title: "Home"
---

# Legged Robots for the Arctic & beyond lab

This is the homepage for NTNU's LRA lab

<!-- Full-width image -->
<div style="width: 100%; text-align: center;">
  <img src="{{ site.baseurl }}/assets/images/lra-logo2.png" alt="NTNU LRA Logo" style="width: 100%; max-width: 100%;">
</div>

## Navigation
- [Team](team/)
- [Robots](robots/)
- [Results](results/)
- [Publications](publications/)


{% for post in paginator.posts %}
  ## {{ post.title }}
  *{{ post.date | date_to_string }}*

  {{ post.content }}
{% endfor %}
