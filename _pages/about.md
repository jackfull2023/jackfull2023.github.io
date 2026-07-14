---
permalink: /
title: "Jack Full"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

欢迎来到我的个人博客。

这里记录技术、学习与思考，主要关注人工智能、软件工程和数据技术。

## 最新文章

{% include base_path %}

{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}
