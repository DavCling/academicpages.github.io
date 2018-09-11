---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my little corner of the web. I am an economic historian and applied microeconomist with research interests in social economics and innovation. I did my Ph.D. in economics at Harvard University. I am Associate Professor of Economics at Case Western Reserve University.

If you peruse my research page you'll see I've published research on language, religious identity, social status, entrepreneurship, and the economic history of India. I use methods ranging from archival research to observational data to field experiments. 

I am currently developing a project about the impact of automation on the labor market in the postwar United States with Leah Boustan.

Selected Publications
--------

{% for post in site.highlights reversed %}
  {% include archive-single.html %}
{% endfor %}