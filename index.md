---
layout: default
title: 文章列表
---

# 我的文章概览

<ul>
{% for post in site.posts %}
<li>
  <a href="{{ post.url }}">{{ post.title }}</a>
  <small style="color: #666;">{{ post.date | date: "%Y-%m-%d" }}</small>
</li>
{% endfor %}
</ul>
