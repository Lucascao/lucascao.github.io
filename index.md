---
layout: page
title: Lucas Cao 的博客
---
{% include JB/setup %}

30来岁青年，头发渐少，住在海边城市。

喜欢美剧、向往健康、便携电子产品控。 

学信息，工作在制造行业，从事一份职业06年至今。

关注 **健康(Fitness)**  \ **效率**  \ **数据科学(Data Science)**  
<br>
<br>
<br>
<br>
### 13年11月开博，用文字记录所见所想。##

<br>


### 最近的文章 ##



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
