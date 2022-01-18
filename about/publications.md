---
layout: page
title: Publications
order: 6
---


{% assign years = site.data.publications.papers | map: "year" | uniq | sort | reverse %}

{% for year in years %}
  <details class="publications-details">
    <summary><span class="publications-year">{{ year }}</span></summary>
      <ul class="publications-list">
        {% assign papers = site.data.publications.papers | where: "year", year %}
        {% for paper in papers %}
          <li class="publications-item">
            <a class="publications-title" href="{{ paper.url }}" target="_blank" rel="noopener noreferrer">{{ paper.title }}</a>
            <p>
              <span class="publications-authors">{{ paper.authors | join: ", " }}</span>
              <br /><span class="publications-journal">{{ paper.journal }}</span>
            </p>
          </li>
        {% endfor %} 
      </ul>
  </details>
{% endfor %}
