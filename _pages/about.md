---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my little corner of the web. I am an applied microeconomist with research interests in economic history, social economics, and innovation. I did my Ph.D. at Harvard University with fields in labor economics, development economics, and economic history. Much of my work draws on earlier training in anthropology and linguistics at the University of Chicago. 

If you peruse my research page you'll see I've published research on language, religious identity, social status, entrepreneurship, and the economic history of India. I use the full range of methods available to the modern economist, from archival research to observational data to field and lab experiments. 

Selected Publications
--------

{% for post in site.highlights reversed %}
  {% include archive-single.html %}
{% endfor %}