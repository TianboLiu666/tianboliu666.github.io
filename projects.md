---
layout: page
title: Projects
permalink: /projects/
---

<!-- <h1>Frist Project</h1> -->
<div class="home">
  <ul class="posts">
    {% for post in site.projects %}
      <li>
        <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        <br>
        {{ post.excerpt }}
        <p></p>
      </li>
    {% endfor %}
  </ul>
</div>
