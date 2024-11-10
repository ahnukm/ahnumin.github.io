---
layout: page
title: "最新进展"
permalink: /news/
---

## 最新进展

以下是项目的最新研究进展，点击每个条目以查看详情：

<ul>
{% for post in site.categories.news %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
  </li>
{% endfor %}
</ul>
