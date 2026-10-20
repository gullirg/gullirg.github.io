---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

My research asks how neural circuits represent space and support navigation, with a focus on grid cells in the entorhinal cortex. I work in the Space &amp; Memory group at the [UCL Institute of Cognitive Neuroscience](https://www.ucl.ac.uk/icn/), supervised by Prof. Neil Burgess, and combine large-scale analysis of neural recordings with computational modelling.

## Where does hexadirectional modulation come from?

Grid cells fire at the vertices of a regular triangular lattice as an animal moves through its environment, and are thought to provide a metric for navigation and memory. In humans, grid cell activity is usually measured indirectly, through **hexadirectional modulation (HexMod)**. HexMod is a six-fold variation of macroscopic signals, such as fMRI, MEG or intracranial recordings, with the direction of movement. It has been used in many laboratories to study the role of grid cells in cognition, development, ageing and disease, but its neuronal origin has been unclear.

Two mechanisms have been proposed:

- **Conjunctive grid × direction cells** whose preferred directions align with the grid axes.
- **Firing rate adaptation**, which reduces firing when grid fields are visited in quick succession, as happens during movement along the grid axes.

We analysed almost 4,000 grid cells recorded from foraging rats. Conjunctive cells' directional tuning was broad and not aligned with the grid axes. Firing, by contrast, was reduced shortly after grid field visits, on a timescale of about a second, consistent with adaptation. Simulations of realistic grid cell populations show that adaptation produces HexMod with the relatively straight trajectories typical of human experiments, but not with the tortuous paths of foraging rats. The simulations also quantify how HexMod depends on grid scale, adaptation time constant and movement speed, and how controlling for variation with location improves its detection.

Together, these results make firing rate adaptation a plausible mechanism for HexMod. They also give a framework for relating human neuroimaging to neuronal activity and for designing experiments that detect grid cells non-invasively.

{% assign hexmod = site.data.publications | where: "id", "reggio2026hexmod" %}
{% for pub in hexmod %}{% include publication.html pub=pub %}{% endfor %}

The rat recordings from Barry et al. (2012) and Ólafsdóttir et al. (2016) analysed in this work are openly available on [Zenodo](https://doi.org/10.5281/zenodo.23477461). The analysis code will be released alongside the preprint.

## Current directions

- The timescale and spatial dependence of adaptation in grid cell populations
- Models that link single-neuron adaptation to population-level hexadirectional signals
- What these mechanisms mean for interpreting human fMRI and MEG studies of grid-like codes
- Spatial and conceptual representations more broadly

## Collaborators

Misun Kim, Zilong Ji and Neil Burgess (UCL Institute of Cognitive Neuroscience), Daniel Bush (UCL Neuroscience, Physiology &amp; Pharmacology), and Caswell Barry (UCL Cell &amp; Developmental Biology).
