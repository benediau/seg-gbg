---
layout: page
title: News
order: 5
---

<div class="posts">
  {% for post in site.posts %}
  <section class="post">
    <header>
      <h4 class="post-title">
        <a href="{{ post.url | absolute_url }}">
          {{ post.title }}
        </a>
      </h4>
    </header>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.excerpt }}

    <footer style="text-align:right;">
      <a href="{{ post.url | absolute_url }}" style="color:#000;"> Read More </a>
    </footer>
  </section>
  {% endfor %}
</div>



<a class="twitter-timeline" href="https://twitter.com/seg_gbg">Tweets by TwitterDev</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>