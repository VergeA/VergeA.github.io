---
layout: page
title: "Blog"
---

This is a placeholder page for what I'm hoping will become a blog! I'm planning to write about programming, homelabs, video games, and other techy topics I'm excited about!

You can check out my latest posts below:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
