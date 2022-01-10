---
layout: page
title: The Team 
order: 2
---



{% for team_member in site.team_members %}
<section>
  <header>
    <h2 style="margin-bottom: 0">{{ team_member.name }}</h2>
    <!-- <h5 style="margin: 0">role: {{ team_member.role }}</h5> -->
  </header>
  
  <div style="display: flex;">
    {% if team_member.image != '' %}
      <div style="margin-top: 1rem; width: 40%; max-width: 12.5rem;">
        <img style="display: block; width: 100%; height: auto;" src="{{ team_member.image }}" />
      </div>
    {% endif %}
    <div style="margin-left: 1rem; width: 100%;">
      {% if team_member.excerpt != '' %}
        <p>{{ team_member.excerpt }}</p>
      {% endif %}
      {% if team_member.description != '' %}
        <p>{{ team_member.description }}</p>
      {% endif %}
    </div>
  </div>
</section>
<hr />
{% endfor %}

