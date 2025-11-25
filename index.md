---
layout: default
title: Roshan's Blog
---

# Welcome

Projects on topics I find interesting - usually hardware, AI, and physics

## Latest Posts

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
  
  {% if post.image %}
  ![{{ post.title }}]({{ post.image }})
  {% endif %}

{% endfor %}
