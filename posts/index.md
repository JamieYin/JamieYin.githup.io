---
layout: archive
title:  "学习笔记"
date:   2017-11-30 22:07:50 +0800
modified:
excerpt: "分为信息可视化笔记和web笔记"
tags: []
image:
  feature: note.gif
  teaser: note.gif
---



在此展示我所触及的笔记


<div class="tiles">
{% for post in site.categories.posts %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 posts 的列出来-->