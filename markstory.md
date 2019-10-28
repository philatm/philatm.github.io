---
layout: page
title: Рассказ
---
<div class="posts">
  <ul>
  {% for post in site.categories.markstory %}
  <li>
  	<span>{{ post.date | date_to_string }}</span>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
  </ul>
</div>