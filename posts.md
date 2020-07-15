---
layout: default
title: All my posts
---

{% for post in site.posts limit:1 %}

<h3><a href= "{{ post.url }}">{{ post.title }}</a></h3>
<p>{{ post.excerpt }}</p>

{% endfor %}
