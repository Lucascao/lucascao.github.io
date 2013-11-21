---
layout: page
title: Lucas Cao 的博客
---
{% include JB/setup %}

0来岁青年，头发不多，住在海边。不抽烟、不喝酒、无不良嗜好，已婚， 有一可爱儿童。

学信息，工作在制造行业，从事一份职业06年至今。

喜欢美剧、向往健康、便携电子产品控。 



### 13年11月开博，用文字记录所见所想。##




### 最近的文章 ##



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
