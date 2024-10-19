---
layout: infolab-toplevel
title: Research
permalink: /research/
header:
  overlay_image: /assets/images/banner_small.jpg
  overlay_filter: "0.4"
toc: true
---

At the Infolab we do research on all aspects of social data science: we define mathematical *models* to represent contemporary social data, so that it can be processed by computers, we develop computational analysis *methods*, we implement our models and methods in publicly available *software*, and we *apply* them to perform empirical social data analyses. These applications allow us to test our theoretical advances and provide requirements for new developments.

## Research areas

Under construction.

## Sponsors

The Infolab is or has been funded by the following projects:

{% for projlist in site.data.projects %}
### {{ projlist.scope }}

{% for proj in projlist.projects %}
**{{ proj.title }}**<br/>
Funding from: {{ proj.funder }}<br/>
Period: {{ proj.years }}<br/>
In short: *{{ proj.description }}*<br/>
{% endfor %}

{% endfor %}


We also thank Uppsala University for providing funding to create the International Master's programme in Data Science (started in the Fall 2020) and our interdisciplinary introductory course on computational social science (first taught in the Spring 2022), and the Division of Computing Science at the Department of Information Technology for continuous support.
