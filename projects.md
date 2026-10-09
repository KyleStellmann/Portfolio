---
layout: default
title: Engineering Projects
permalink: /projects/
---
{% for post in site.posts offset:1 %}
  {% include featured-post.html %}
{% endfor %}
