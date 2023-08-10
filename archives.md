---
title: Archives
layout: page
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title | smartify }}</a>
    </li>
  {% endfor %}
</ul>
