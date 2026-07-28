---
layout: page
permalink: /blog/
title: blog
description: Research notes and technical explanations.
nav: true
nav_order: 1
---

{% assign visible_posts = site.posts | where_exp: "post", "post.published != false" %}

{% if visible_posts.size > 0 %}
<div class="post-list">
  {% for post in visible_posts %}
    <article style="margin-bottom: 1.8rem;">
      <h2 style="margin-bottom: 0.25rem;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p style="margin-bottom: 0.35rem; color: var(--global-text-color-light);">{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.description }}</p>
    </article>
  {% endfor %}
</div>
{% else %}
<p>No public posts yet.</p>
{% endif %}
