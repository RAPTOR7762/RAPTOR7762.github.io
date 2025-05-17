---
layout: blog
title: "Blog"
---
Welcome to my blog!  
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
