---
layout: page
permalink: /blog/
title: Blog
nav: true
nav_order: 4
description: Notes on biostatistics, clinical trials, research, and academic life.
---

<style>
  :root {
    --global-theme-color: #012169;
    --global-hover-color: #00539b;
  }

  .post-title {
    font-weight: 700;
  }

  .post-header .desc,
  .post h2 {
    font-size: 1.35rem;
    font-weight: 600;
  }
</style>

{% assign personal_posts = site.posts | where: "author", "Peijin Wang" %}

{% if personal_posts.size > 0 %}
  <div class="post-list">
    {% for post in personal_posts %}
      <article class="mb-5">
        <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
        {% if post.description %}
          <p>{{ post.description }}</p>
        {% elsif post.excerpt %}
          {{ post.excerpt }}
        {% endif %}
      </article>
    {% endfor %}
  </div>
{% else %}
  <p>No posts yet. New writing on biostatistics, clinical trials, and research will appear here.</p>
{% endif %}
