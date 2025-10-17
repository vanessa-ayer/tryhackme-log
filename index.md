---
layout: default
title: 'Rooms'
---

<p class="tagline">
  A terminal-style log documenting my TryHackMe adventures, one room at a time...
</p>

<h2 class="type-header" data-text="$ rooms">
  <span class="type-target"></span><span class="cursor"></span>
</h2>

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%b %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
