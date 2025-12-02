---
layout: page
title: "Blog"
---

Welcome to my blog! I'm planning to write about programming, homelabs, video games, and other techy topics.

You can check out my latest posts below:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
