---
layout: home
title: 欢迎来到我的博客
permalink: /
---

# 欢迎来到我的个人博客

这里是我分享技术文章、生活感悟和学习心得的地方。

## 最新文章

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%Y-%m-%d" }} - {{ post.excerpt | strip_html | truncate: 150 }}
{% endfor %}
