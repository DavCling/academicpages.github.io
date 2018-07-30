---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my little corner of the web. I am an applied microeconomist at Case Western Reserve University. My research interests span social economics, economic history, and innovation. I did my Ph.D. at Harvard University. Some of my work draws on earlier training in anthropology and linguistics at the University of Chicago. 

If you peruse my research page you'll see I've published research on language, religious identity, social status, entrepreneurship, and the economic history of India. I use methods ranginf from archival research to observational data to field experiments. 

Selected Publications
--------

{% for post in site.highlights reversed %}
  {% include archive-single.html %}
{% endfor %}