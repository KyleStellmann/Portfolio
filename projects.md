---
layout: default
title: Engineering Projects
permalink: /projects/
---
<style>
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 24px;
    width: 100%;
    margin-top: 30px;
    box-sizing: border-box;
  }

  .project-card {
    border: 1px solid #e2e8f0;
    border-radius: 6px;
    padding: 18px;
    background: #ffffff;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    font-family: 'Times New Roman', Times, serif;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
  }

  .project-card-image-wrapper {
    display: block;
    width: 100%;
    height: 200px;
    overflow: hidden;
    margin-bottom: 15px;
  }

  .project-card-image-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: contain;
    display: block;
  }

  .project-card-title {
    font-family: 'Times New Roman', Times, serif;
    font-size: 1.1rem;
    margin: 0;
    font-weight: bold;
    text-align: center;
  }

  .project-card-title a {
    color: inherit;
    text-decoration: none;
  }
</style>

<div class="projects-grid">
  {% for post in site.posts offset:1 %}
    <div class="project-card">
      {% if post.image %}
        <a href="{{ site.github.url }}{{ post.url }}" class="project-card-image-wrapper">
          <img src="{{ site.github.url }}/assets/img/{{ post.image }}" alt="{{ post.title }}">
        </a>
      {% endif %}

      <h3 class="project-card-title">
        <a href="{{ site.github.url }}{{ post.url }}">{{ post.title }}</a>
      </h3>
    </div>
  {% endfor %}
</div>
