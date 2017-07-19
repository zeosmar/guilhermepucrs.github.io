---
layout: default
title: Guilherme
---

Hi. I am Guilherme Fróes Silva, a Master's Student in Electrical Engineering within the Graduate Program in Electrical Engineering in PUCRS - Brasil.

Check the latest of what I've been writing about:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
