---
layout: single
title: Publications
permalink: /publications/
---
{% include base_path %}

<p>
  For the full publication list, please see my 
  <a href="https://scholar.google.com/citations?user=tvgmOGAAAAAJ&hl=en" target="_blank">Google Scholar profile</a>
  or the 
  <a href="https://publications.lboro.ac.uk/publications/all/collated/ttcl3.html" target="_blank">university repository</a>.
</p>

<h2>Recent and Featured Papers</h2>

{% assign grouped_publications = site.publications | group_by: "year" %}
{% assign sorted_groups = grouped_publications | sort: "name" | reverse %}

{% for group in sorted_groups %}
  {% assign year = group.name | year: "%Y" %}
  <h3>{{ year }}</h3>
  <div class="publications-list">
    {% for publication in group.items %}
      {% include publication-entry.html publication=publication %}
    {% endfor %}
  </div>
{% endfor %}