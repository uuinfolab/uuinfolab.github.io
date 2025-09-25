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

# Research areas

<ul>
  <li><b>Social network analysis:</b> we develop models to analyse feature-rich social networks, such as multilayer, temporal, communication, and probabilistic networks, to capture the complexity of contemporary social data. We focus on aspects such as scalability, performance, and fairness.</li>
    <li><b>Social content analysis:</b> we develop models to analyse the rich variety of human-generated data, such as images shared online, videos in video-first platforms, and podcasts. We focus on aspects such as connotativity, steerability, and bias.</li>
  <li><b>Social cybersecurity:</b> we study how humans can be compromised in online environments, for example through online disinformation and inauthentic coordinated information spreading, hate speech, or linguistic manipulation.</li>
  <li><b>Visual political communication:</b> we study how visual content is used online to communicate, aggregate, polarise, and persuade.</li>
  <li><b>Population-scale social networks:</b> we work with a network of the whole Swedish adult population to study Nation-scale social structure and processes.</li>
</ul>

{% for area in site.data.areas %}
<article class="research-box">
<a href="{{ area.url }}" class="research-text research-box">
     <figure class="no-margins">
         <div class="research-box">
             <img src="{{ area.img }}" class="research-img" alt="Feature-rich networks"/>
         </div>
     </figure>
     <div class="pull-up">
         <h2 class="research-text-size text-in-img research-header">{{ area.name }}</h2>
         <div class="margin-b">
         {{ area.description }}
         </div>
     </div>
</a>
</article>
{% endfor %}
               

# Sponsors

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
