---
title: Learning Blog
---

# So I'm going to learn more about Machine learning

And this is the blog that I will use to track my progress.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
