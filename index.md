---
layout: default
title: My Blogs
---

# Just my first new Blog

<div style="display: none;">

  ## Markdown Sheet

  <ul class="posts">
    {% for post in site.posts reversed %}
      {% if post.tags contains "markdown" %}
      <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.index_title }}</a> ({{ post.date | date_to_string }})</li>
      {% endif %}
    {% endfor %}
  </ul>
</div>
