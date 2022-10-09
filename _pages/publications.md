---
permalink: /publications/
title: "Publications"
layout: publications
publications:
  - title: "test"
    authors: test1, test2, test3
    venue: "IEEE International Conference on"
    doi:  
    year: 2022
    type: conferences
  - title: test
    authors: CL
    venue: IEEE
    doi: 
    year: 2022
    type: journal
---


{% include base_path %}

{% for post in site.publications reversed %} {% include archive-single.html %} {% endfor %}
