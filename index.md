
---
layout: default
title: Home
---

# Welcome to My Portfolio

I am an engineering student at the University of Connecticut with an interest in problem-solving, mathematics, physics, and applying engineering concepts to real-world challenges.

## About Me

This portfolio showcases my education, technical skills, and projects as I continue developing my experience as an engineer. I look forward to gaining hands-on experience and preparing for future internship opportunities.

## Blog Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

{% endfor %}
