---
layout: default
title: Computation Blog
---

# Welcome

Exploring the intersection of computation across physics, hardware design, AI, and neuroscience.

## Latest Posts

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
  
  {% if post.image %}
  ![{{ post.title }}]({{ post.image }})
  {% endif %}

{% endfor %}
