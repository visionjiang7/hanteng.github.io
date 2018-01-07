---
layout: archive
title: "note （note）"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "我的网页设计笔记"
tags: []
image: 
  feature:1.jpg
  teaser:1.jpg
---


<div class="tiles">
{% for post in site.categories.web note %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->