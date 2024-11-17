---
layout: default
title: Archive
permalink: /archive/
---

<div class="page-title-container">
  <div class="heading-container">
    <h1>{{ page.title }}</h1>
  </div>
</div>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%d %b %Y" }}</span>
    </li>
  {% endfor %}
</ul>