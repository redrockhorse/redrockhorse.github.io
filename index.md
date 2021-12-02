---
layout: default
title: 理则顿悟，乘悟并消；事资渐修，因次第尽
---
<p><br /><b>My Blog:</b></p>
<p>{{site.time}}</p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="#">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

