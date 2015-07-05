---
layout: archive
title: Log
permalink: /log/
---
<section class="site-front block">
  <div class="container home-group">
    {% for post in site.categories.log %}
        <!-- <div class="grid_6"> -->
          <!--  -->
        <!-- </div> -->
        <!-- <div class="grid_2">{{ post.date | date: "%b %-d, %Y" }}</div> -->
        <div class="grid_9"><h3 class="home-list">&nbsp;&bull;&nbsp; <a href="{{ post.url }}">{{ post.title }}</a></h3></div>
        <div class="grid_1">{{ post.category }}</div>
        <div class="grid_2">{{ post.date | date: "%d-%m-%Y" }}</div>
    {% endfor %}
  </div>
</section>