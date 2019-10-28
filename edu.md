---
layout: page
title: Мое обучение
---
<div class="posts">
  <ul>
  {% for post in site.categories.edu %}
  <li>
  	<span>{{ post.date | date_to_string }}</span>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
  </ul>
</div>