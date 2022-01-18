---
layout: page
title: NOBROOK
order: 4
---

## *Evaluating removal methods of the invasive Brook trout and effects of removal on the ecosystem*

The overall aim of the NOBROOK project is to develop new methods for removal of the invasive brook trout and to evaluate the effect of removal on ecosystems. Through establishing several control populations of known phenotypical distribution and a combination of brown trout in allopatry and in sympatry with brook trout be able to compare and test different removal methods across species and phenotypical traits. The response and recovery of the ecosystem after removal will we examined by investigating the composition of benthic invertebrates and fish diets as well as the potential impact presence of brook trout may have on the interaction between brown trout and the endangered freshwater pearl mussel. The results will provide insights into the resilience of stream ecosystems and be helpful in efforts to restore and maintain the important ecosystem services and biodiversity connected to these habitats.

<p class="sponsors">
  <a href="https://www.naturvardsverket.se/">
    <img alt="" src="https://user-images.githubusercontent.com/96004332/149932141-fc1e04e5-d0bd-49b0-b392-814bc1c4b163.png" />
  </a>
  <a href="https://formas.se/">
    <img alt="" src="https://user-images.githubusercontent.com/96004332/149924302-a5e85e43-f5f8-4b2f-b1d3-dc389238b59d.png" />
  </a>
</p>

---

<aside class="posts">
  <header>
    <h4>News</h4>
  </header>

  {% for post in site.categories.nobrook %}
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
</aside>

