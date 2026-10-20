---
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}{{ site.author.cv }}" class="btn btn--primary"><i class="fas fa-download" aria-hidden="true"></i>&nbsp; Download CV (PDF)</a>

## Research interests

Computational models of how the brain forms cognitive maps from first-person experience: egocentric–allocentric reference frame transformations, spatial memory and imagery, and the relation between navigation in physical space and in abstract, conceptual spaces.

## Education

<ul class="timeline">
  <li>
    <div class="timeline__when">2023 – 2027</div>
    <div class="timeline__what">
      <strong>PhD in Cognitive Neuroscience</strong>, UCL Institute of Cognitive Neuroscience
      <p>Computational models of spatial cognition: egocentric–allocentric transformations, cognitive maps and grid cells. Supervisor: Prof. Neil Burgess. Upgraded from MPhil to PhD in April 2025; expected completion 2027.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">2020 – 2021</div>
    <div class="timeline__what">
      <strong>MSc Machine Learning</strong> (Merit), University College London
      <p>Thesis: “Manifold Alignment in Hyperbolic Space”. Supervisor: Prof. Bradley Love.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">2017 – 2020</div>
    <div class="timeline__what">
      <strong>BSc Physics with Theoretical Physics</strong> (First-Class Honours), King’s College London
      <p>Thesis: “Cellular Computing &amp; Artificial Cells”. Supervisor: Prof. Mark Green.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">2014 – 2017</div>
    <div class="timeline__what">
      <strong>BA Philosophy</strong> (108/110), Università Vita-Salute San Raffaele, Milan
      <p>Thesis: “When Matter Thought Itself”. Supervisor: Prof. Gianvito Martino.</p>
    </div>
  </li>
</ul>

## Publications

{% for pub in site.data.publications %}{% if pub.type == "preprint" %}{% include publication.html pub=pub %}{% endif %}{% endfor %}

## Conference contributions

{% for pub in site.data.publications %}{% unless pub.type == "preprint" %}{% include publication.html pub=pub %}{% endunless %}{% endfor %}

<p class="pub-footnote">* Equal contribution.</p>

### Meetings attended

<ul class="timeline">
  <li>
    <div class="timeline__when">Jun 2026</div>
    <div class="timeline__what">7th International Conference on the Mathematics of Neuroscience and AI, Rome, Italy</div>
  </li>
  <li>
    <div class="timeline__when">Sep 2023</div>
    <div class="timeline__what">Neuro-AI Talks (NEAT), Osnabrück, Germany</div>
  </li>
</ul>

## Research experience

<ul class="timeline">
  <li>
    <div class="timeline__when">2023 – present</div>
    <div class="timeline__what">
      <strong>Doctoral Researcher</strong>, Space &amp; Memory Group, UCL Institute of Cognitive Neuroscience
      <p>Models of how egocentric experience is transformed into allocentric cognitive maps, extending the Bicanski &amp; Burgess model of spatial memory and imagery to spatial view cells. Population models and recordings of grid cells to identify the neuronal origin of hexadirectional modulation.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">2022 – 2023</div>
    <div class="timeline__what">
      <strong>Research Assistant</strong>, UCL Queen Square Institute of Neurology, with the Space &amp; Memory Group
      <p>Firing rate adaptation and hexadirectional modulation in rodent grid cell recordings. Supervisor: Prof. Neil Burgess.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">Summer 2020</div>
    <div class="timeline__what">
      <strong>Research Intern</strong>, Burak Lab, The Hebrew University of Jerusalem (remote)
      <p>Ring attractor network model of place cells. Supervisor: Prof. Yoram Burak.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">Summer 2019</div>
    <div class="timeline__what">
      <strong>Summer Material Analyst</strong>, Fermi National Accelerator Laboratory, USA
      <p>Surface roughness in nitrogen-doped SRF cavities, Applied Physics &amp; Superconducting Technology Division. Supervisor: Dr Anna Grassellino.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">Summer 2019</div>
    <div class="timeline__what">
      <strong>Research Fellow</strong>, Randall Centre for Cell &amp; Molecular Biophysics, King’s College London
      <p>Robustness of Turing patterns in reaction-diffusion systems on complex networks. Supervisor: Dr Attila Csikász-Nagy.</p>
    </div>
  </li>
</ul>

## Teaching

<ul class="timeline">
  <li>
    <div class="timeline__when">2023 – 2026</div>
    <div class="timeline__what">
      <strong>Postgraduate Teaching Assistant</strong>, NEUR0016 Neural Computation: Models of Brain Function, UCL
      <p>Undergraduate tutorial groups, coursework essay marking and exam marking.</p>
    </div>
  </li>
  <li>
    <div class="timeline__when">2023 – present</div>
    <div class="timeline__what">
      <strong>Executive Training Demonstrator</strong>, UCL Division of Psychology &amp; Language Sciences
      <p>Support for the Division’s executive education in behavioural science (UCL Changing Minds short courses, UCL Behavioural Insights Hub).</p>
    </div>
  </li>
</ul>

## Awards and funding

<ul class="timeline">
  <li>
    <div class="timeline__when">2023 – 2027</div>
    <div class="timeline__what">Executive Training Demonstrator Studentship, UCL Division of Psychology &amp; Language Sciences (PhD fees and stipend)</div>
  </li>
  <li>
    <div class="timeline__when">2024</div>
    <div class="timeline__what">Guarantors of Brain Travel Award (iNAV 2024)</div>
  </li>
  <li>
    <div class="timeline__when">2019</div>
    <div class="timeline__what">King’s Experience Research Award, King’s College London</div>
  </li>
</ul>

## Other experience

<ul class="timeline">
  <li>
    <div class="timeline__when">2025 – present</div>
    <div class="timeline__what"><strong>Co-Founder &amp; Director</strong>, The Collective Ventures Ltd<p>Music and arts events.</p></div>
  </li>
  <li>
    <div class="timeline__when">2019 – 2020</div>
    <div class="timeline__what"><strong>Co-Founder &amp; CEO</strong>, Mappin Technologies Ltd<p>Indoor navigation, asset tracking and contagion monitoring for large venues (Kings20 and Geovation accelerators).</p></div>
  </li>
</ul>

## Skills

<ul class="timeline">
  <li>
    <div class="timeline__when">Programming</div>
    <div class="timeline__what">Python (computational modelling and simulation of neural circuits, statistical modelling of neural data); Julia, MATLAB, Fortran; Git, LaTeX, Linux</div>
  </li>
  <li>
    <div class="timeline__when">Languages</div>
    <div class="timeline__what">Italian (native), English (fluent), French (working proficiency)</div>
  </li>
</ul>
