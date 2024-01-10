---
layout: page
title: Publications
permalink: /publications/
---

<!-- <h1>Publications</h1> -->

  <ul class="posts">
    {% for post in site.publications %}
      <li>
        <!-- <a href="{{post.paperurl}}"><h3 style="color:black;font-size:23px;">{{ post.title }}</h3> </a> -->
        <!-- <a href="{{post.url}}"><h3 style="color:black;font-size:23px;">{{ post.title }}</h3> </a> -->
        <a href="{{post.url}}"><h3>{{ post.title }}</h3> </a>
        <p>{{ post.auther}}</p> 
        <p>{{ post.venue}}</p> 
      </li>
    {% endfor %}
  </ul>
