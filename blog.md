---
layout: home
title: "Blog"
permalink: /blog/
pagination:
  enabled: true
---

My latest posts and write-ups on security, cloud, personal experiments, and whatever else is on my mind.

{% for post in site.posts %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p><small>Published on {{ post.date | date: "%B %d, %Y at %I:%M %p" }}</small></p>
  <p>{{ post.excerpt }}</p>
{% endfor %}
