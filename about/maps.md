---
layout: page
title: MAPS
---

## *Migratory patterns and productivity potential of juvenile sea trout*

The MAPS project is a PhD project looking to answer questions relating to the downstream migration of brown trout as smolts. There two main avenues of interest: building a model to predict smolt productivity and assessing differences between offspring of long and short distance migrants.

Once brown trout smoltify and migrate to the sea it is known as sea trout. Sea trout are a valuable migratory species both in terms of economics and ecosystem services thus research that can aid management programmes and restoration projects is vital. Investigating patterns during downstream migration of smolts and developing more accurate models of smolt production will provide key information to benefit sea trout.

This project will examine smolt production potential with the aim to produce a standardised method for assessing productivity and reveal associations with habitat quality. Smolt traps will be run in streams across the sea trouts natural range to give estimates of juvenile densities. Each stream will be habitat mapped in detail including measures such as flow, connectivity and canopy cover. The juvenile densities and habitat mapping will combined into a model.

Telemetry will provide a wealth of movement data from streams across Europe. Data from a wide latitude and temperature gradient will be used to make predictions about migratory patterns in relation to climate change.

Mechanisms behind differing migration strategies will be questioned in behavioural and physiological experimental studies, in particular offspring of long and short distance migrants will be compared to determine underlying factors relating to variation in migration distance. When sea trout return from the marine environment they can migrate upstream a few hundred metres or many kilometres.

---

<aside class="posts">
  <header>
    <h4>News</h4>
  </header>

  {% for post in site.categories.maps %}
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
