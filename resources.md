---
layout: page
title: Resources
permalink: /resources/
---

Here you can find my resume and other materials.

<ul class="post-list">
  {% for post in site.categories.resources %}
    <li>
      <h3>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>