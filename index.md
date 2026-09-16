---
layout: default
title: Landing
---

# Welcome to davo.lt
*Enjoy your stay?*

<h2>Recent Articles</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
