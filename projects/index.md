---
layout: page
title: Projects
order: 2
---

<div class="posts">
  {% for post in site.tags.project %}
  <section class="post">
    <header>
      <h4 class="post-title">
        <a href="{{ post.url | absolute_url }}">
          {{ post.title }}
        </a>
      </h4>
    </header>

    {{ post.excerpt }}

    <footer style="text-align:right;">
      <a href="{{ post.url | absolute_url }}" style="color:#000;"> Read More </a>
    </footer>
  </section>
  {% endfor %}
</div>
