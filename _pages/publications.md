---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /outputs/
---

{% include base_path %}

<div class="page__content">

<p>Also on <a href="{{ site.author.googlescholar }}">Google Scholar</a> and <a href="{{ site.author.orcid }}">ORCID</a>.</p>

<h2>Preprints and papers</h2>
{% assign papers = site.data.publications | where: "type", "preprint" %}
{% for pub in papers %}{% include publication.html pub=pub %}{% endfor %}

<h2>Conference contributions</h2>
{% for pub in site.data.publications %}{% unless pub.type == "preprint" %}{% include publication.html pub=pub %}{% endunless %}{% endfor %}

<p class="pub-footnote">* Equal contribution.</p>

</div>
