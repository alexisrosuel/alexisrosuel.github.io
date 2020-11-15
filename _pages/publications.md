---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
So far, the topics I have worked on include:

- Linear Spectral Statistics of large spectral coherency matrices;
- Signal detection in high-dimensional time series through the so-called random matrix spike models;
- Asymptotic distribution of the largest entry of spectral coherency matrices.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
