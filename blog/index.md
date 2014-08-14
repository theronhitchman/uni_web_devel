---
layout: blog
title: Circles and Tangents
---


  <div class="posts">
    {% for post in site.posts limit 10 %}
      <h4><a href="{{ post.url | prepend: site.baseurl }}">
        {{ post.date | date: "%b %-d, %Y" }}: {{ post.title }}</a></h4>

      {{ post.excerpt }}

    {% endfor %}
  </div>
