---
layout: page
title: Рассказ
---
<div class="posts">
  <ul>
  {% for post in site.categories.markstory %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date_to_string }}</span>
  </li>
  {% endfor %}
  </ul>
</div>