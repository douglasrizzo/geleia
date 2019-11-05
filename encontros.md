---
layout: page
title: Encontros
permalink: /encontros/
---
<ul>
  {% for post in site.categories.encontros %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>