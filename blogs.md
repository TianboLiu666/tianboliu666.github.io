---
layout: page
title: Blogs
permalink: /blogs/
---

<!-- <h1>Frist Project</h1> -->

  <ul class="posts">
    {% for post in site.posts %}
      <li>  
      <a href="{{ post.url }}"><h3>{{ post.title }}</h3></a>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>
<!-- permalink: /publications/:title -->
