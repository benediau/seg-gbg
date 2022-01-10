---
layout: page
title: MAPS
order: 3
---

## *Migratory patterns and productivity potential of juvenile sea trout*

The MAPS project is a PhD project looking to answer questions relating to the downstream migration of sea trout. There two main avenues of interest: building a model to predict smolt productivity and assessing differences between offspring of long and short distance migrants. 

Sea trout are a valuable migratory species that provides both economic and ecosystem services. They are under threat from numerous angles including: climate change, aquaculture and habitat destruction. Thus research that can help protect them by guiding management/restoration projects is vital. During migration from a freshwater environment to marine environment is a period of extreme vulnerability and understanding what happens during this time is key to boosting population numbers. 

This project will examine smolt production potential with the aim to produce a standardised method for assessing productivity and reveal associations with habitat quality. Smolt traps will be run in streams across the sea trouts natural range to give estimates of juvenile densities. Each stream will be habitat mapped in detail including and combined with juvenile density data to create a predictive model. 
Mechanisms behind differing migration strategies will be questioned in behavioural and physiological studies, in particular offspring of long and short distance migrants will be compared. When sea trout return from the marine environment they can migrate upstream a few hundred metres or many kilometres, this research will reveal whether the there are differences in the offspring related to variation in migration distance of the parents.  

Telemetry will provide a wealth of movement data from streams across Europe with a particular focus on migration timings and residency vs. anadromy. Using in stream PIT antenna systems we will be able to closely monitor movement within streams and analyse differences between individuals, for example whether there is a sex bias in migrants, or if age at first migration differs between countries. 


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
