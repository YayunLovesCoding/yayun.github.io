---
layout: page
title: "中文"
permalink: /chinese
---

just a human on this planet
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
