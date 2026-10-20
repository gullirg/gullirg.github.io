---
permalink: /
title: "Guglielmo Reggio"
excerpt: "PhD candidate in computational neuroscience at the UCL Institute of Cognitive Neuroscience."
author_profile: true
hide_title: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<p class="lead">I am a PhD candidate in computational neuroscience at the <a href="https://www.ucl.ac.uk/icn/">UCL Institute of Cognitive Neuroscience</a>, working with <a href="https://www.ucl.ac.uk/brain-sciences/icn/research/research-groups/space-memory/neil-burgess">Prof. Neil Burgess</a> in the Space &amp; Memory group.</p>

I study how the brain represents space. My current work asks where *hexadirectional modulation* comes from: this six-fold signal is the standard way to detect grid cell activity non-invasively in humans. To answer this, I analyse thousands of grid cells recorded in rats and simulate grid cell populations. The work shows that firing rate adaptation can produce the signal, and it links single-neuron mechanisms to human neuroimaging. [More about my research →]({{ base_path }}/research/)

My background is interdisciplinary. I studied philosophy at Università Vita-Salute San Raffaele, theoretical physics at King's College London, and machine learning at UCL.

<ul class="interests">
  <li>Grid cells</li>
  <li>Hexadirectional modulation</li>
  <li>Firing rate adaptation</li>
  <li>Spatial navigation &amp; cognitive maps</li>
  <li>Computational modelling</li>
  <li>Neural data analysis</li>
</ul>

## News

<ul class="news">
{% for item in site.data.news %}
  <li>
    <time datetime="{{ item.date }}">{{ item.date | append: "-01" | date: "%b %Y" }}</time>
    <p>{{ item.text | markdownify | remove: "<p>" | remove: "</p>" | strip }}</p>
  </li>
{% endfor %}
</ul>

## Selected publications

{% assign selected = site.data.publications | where: "selected", true %}
{% for pub in selected %}
  {% include publication.html pub=pub %}
{% endfor %}

<p class="section-link"><a href="{{ base_path }}/publications/">All publications and conference contributions →</a></p>
