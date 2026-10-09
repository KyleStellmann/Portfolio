---
layout: default
title: Engineering Projects
permalink: /projects/
---
<style>
  /* Force all posts in this loop to center text and images */
  .projects-feed > div {
    text-align: center !important;
  }
  .projects-feed img {
    margin: 0 auto !important;
  }
  
  /* Hide the Contact Me / Projects button row */
  .projects-feed div[style*="display: flex"],
  .projects-feed div[style*="display:flex"] {
    display: none !important;
  }
</style>

<!-- Added margin-top: 50px here to create top spacing -->
<div class="projects-feed" style="margin-top: 50px;">
  {% for post in site.posts offset:1 %}
    {% include featured-post.html %}
  {% endfor %}
</div>
<div class="projects-feed">
  {% for post in site.posts offset:1 %}
    {% include featured-post.html %}
  {% endfor %}
</div>
