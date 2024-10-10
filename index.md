---
layout: default
title: "Home"
---
<!-- Full-width image -->
<div style="width: 50%; text-align: center;">
  <img src="{{ site.baseurl }}/assets/images/lra-logo2.png" alt="NTNU LRA Logo" style="width: 100%; max-width: 100%;">
</div>

Welcome to the Legged Robots for the Arctic & beyond lab! We are a new group of researchers and students at NTNU currently kickstarting our activities in legged robots for extreme environments and tasks. Our "home" is at the Department of Engineering Cybernetics.

<img src="{{ site.baseurl }}/assets/images/olympus_views.png" alt="Views of Olympus" style="width: 80%; max-width: 800px;">

Our current activities relate to jumping quadrupeds, their design optimization, jumping policies and in-flight attitude stabilization to prepare safe landing. Space applications currently drive our developments. Future activities shall also include interacting with icy terrain and snow. 

Results from our work are presented in the relevant section of this site, while below you can find an exploded view of "Olympus", our main design as of today, alongside one of our indicative results. 

<div style="display: flex; justify-content: space-between;">

<!-- embed Olympus exploded view video -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fXCZ70AGQOE?si=yOiL7rOa3UzqGwjT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!-- Eurepus result -->
<div style="width: 48%;">
    <iframe width="100%" height="315" src="https://www.youtube.com/embed/5qNPCH34M2M?si=IzvN3GhEk5WNgaXR" 
            title="YouTube video player" frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
            referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

</div>

{% for post in paginator.posts %}
  ## {{ post.title }}
  *{{ post.date | date_to_string }}*

  {{ post.content }}
{% endfor %}
