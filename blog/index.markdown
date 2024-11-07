---
layout: default
title: Blog
---

# Blog

Welcome to my blog. Here are my posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

## Pages
- [About]({{ site.baseurl }}/about)