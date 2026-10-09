---
layout: default
title: Engineering Projects
permalink: /projects/
---
<div class="centered-posts">
  {% for post in site.posts offset:1 %}
    {% include featured-post.html %}
  {% endfor %}
</div>

<style>
  .centered-posts > div {
    text-align: center !important;
  }
  .centered-posts img {
    margin: 0 auto !important;
  }
</style>
