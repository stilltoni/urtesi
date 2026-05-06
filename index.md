---
layout: default
title: Home
---

# Artikujt e fundit

{% for post in site.posts %}
<div class="post-card">
  <a href="{{ post.url }}">{{ post.title }}</a>
  <div class="post-date">{{ post.date | date: "%d %B %Y" }}</div>
</div>
{% endfor %}
