---
layout: default
title: 理则顿悟，乘悟并消；事资渐修，因次第尽
---
<p><br /><b>My Blog:</b></p>
  <ul class="post">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

