---
layout: default
title: My Blogs
---

<aside class="greeting">Happy New Year 2019! C'Est La Vie!</aside>

# Welcome to my blogs (Some of them aren't avaliable yet)

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
