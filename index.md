
---
layout: default
title: Home
---

# Welcome to My Portfolio

I am an engineering student at the University of Connecticut.

## About Me

This website showcases my education, projects, skills, and experiences.

## Blog Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

{% endfor %}
