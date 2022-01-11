---
layout: page
title: The Team 
order: 2
---



{% for team_member in site.data.team.members %}
<section class="team-member">
  <header>
    <h3 class="team-member-name">{{ team_member.name }}</h3>
    <!-- <h5 class="team-member-role">role: {{ team_member.role }}</h5> -->
  </header>
  
  <div class="team-member-content">
    {% if team_member.image != '' %}
      <div class="team-member-image">
        <img src="{{ team_member.image }}" />
      </div>
    {% endif %}
    <div class="team-member-body">
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

