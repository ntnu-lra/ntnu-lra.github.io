---
layout: default
title: "Home"
---
<!-- Full-width image -->
<div style="width: 50%; text-align: center;">
  <img src="{{ site.baseurl }}/assets/images/lra-logo2.png" alt="NTNU LRA Logo" style="width: 100%; max-width: 100%;">
</div>

Welcome to the Legged Robots for the Arctic & beyond lab! We are a group of researchers and students at NTNU kickstarting our activities in legged robots for extreme environments and tasks. 

<img src="{{ site.baseurl }}/assets/images/olympus_views.png" alt="Views of Olympus" style="width: 80%; max-width: 800px;">

Our current activities relate to jumping quadrupeds, their design optimization, jumping policies and in-flight attitude stabilization to prepare safe landing. Future activities shall also include interacting with icy terrain and snow. 


{% for post in paginator.posts %}
  ## {{ post.title }}
  *{{ post.date | date_to_string }}*

  {{ post.content }}
{% endfor %}
