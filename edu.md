---
layout: page
title: Мое обучение
---
<div class="posts">
  <ul>
  {% for post in site.categories.edu %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date_to_string }}</span>
  </li>
  {% endfor %}
  </ul>
</div>