---
permalink: /
title: "Guglielmo Reggio"
excerpt: "PhD candidate in computational neuroscience at UCL, building models of how the brain forms cognitive maps from first-person experience."
author_profile: true
hide_title: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<p class="lead">I am a PhD candidate in computational neuroscience at the <a href="https://www.ucl.ac.uk/icn/">UCL Institute of Cognitive Neuroscience</a>, working with <a href="https://www.ucl.ac.uk/brain-sciences/icn/research/research-groups/space-memory/neil-burgess">Prof. Neil Burgess</a> in the Space &amp; Memory group.</p>

I build computational models of how the brain turns first-person experience into cognitive maps. One question is how egocentric, self-centred sensory input is transformed into allocentric, world-centred representations of space, and back again when we remember or imagine a place. Another is whether the same machinery lets us navigate abstract, conceptual spaces as well as physical ones.

I test these models against neural data. In my first paper, simulations of grid cell populations and recordings of thousands of grid cells show that firing rate adaptation can explain *hexadirectional modulation*, the signal used to detect grid cells in human neuroimaging. [More about my research →]({{ base_path }}/research/)

My background is interdisciplinary. I studied philosophy at Università Vita-Salute San Raffaele, theoretical physics at King's College London, and machine learning at UCL.

<ul class="interests">
  <li>Computational modelling</li>
  <li>Cognitive maps</li>
  <li>Egocentric–allocentric transformations</li>
  <li>Spatial memory &amp; imagery</li>
  <li>Conceptual navigation</li>
  <li>Grid cells</li>
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
