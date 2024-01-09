---
layout: default
title: Projects
permalink: /projects/
includelink: true
---

<h1>Frist Project</h1>


  <ul class="posts">
    {% for post in site.projects %}
      <li>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>
