---
layout: page
title: "Blog"
permalink: /blog/
---

## Blog

Thoughts on software engineering, tools, and the craft of building things.

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span> —
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
