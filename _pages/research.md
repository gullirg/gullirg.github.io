---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

We experience the world from a first-person perspective, yet we can plan routes we have never taken, imagine places from new viewpoints, and organise knowledge as if it were a map. My research asks how the brain abstracts from egocentric experience to these cognitive maps, and whether the same computations support navigation in physical and in abstract, conceptual spaces.

I work in the Space &amp; Memory group at the [UCL Institute of Cognitive Neuroscience](https://www.ucl.ac.uk/icn/), supervised by Prof. Neil Burgess. My approach is computational: I build models of neural circuits and test them against neural recordings and human data.

## From egocentric experience to allocentric maps

The hippocampal formation holds world-centred (allocentric) representations of space, such as place, grid, head-direction and boundary cells. Perception and action, however, are organised around the body (egocentric). How are allocentric maps derived from egocentric sensory input, and how are they turned back into first-person scenes when we remember or imagine a place?

I work with the neural-level model of spatial memory and imagery of [Bicanski &amp; Burgess (2018)](https://doi.org/10.7554/eLife.33752). In that model, a transformation circuit driven by head direction links egocentric and allocentric representations. My current work extends this framework to *spatial view cells* in primates. These cells respond to the allocentric location being looked at, even when it is not visible. The aim is a single model that explains how such responses arise from conjunctive coding of identity, location and direction.

## Spatial and conceptual navigation

The hippocampal–entorhinal system that supports spatial navigation is also engaged when we organise knowledge: when we "navigate" spaces of concepts, tasks or social relations. I am interested in whether the same computational principles, such as map-like codes and predictive representations, explain navigation in both kinds of space. I am also interested in the geometry of these representations. Hierarchical knowledge, for example, embeds more naturally in hyperbolic than in Euclidean space, which was the topic of my MSc work on aligning conceptual systems in hyperbolic space.

## Grid cells and hexadirectional modulation

In humans, grid cell activity is usually measured indirectly through **hexadirectional modulation (HexMod)**, a six-fold variation of fMRI, MEG or intracranial signals with movement direction. Its neuronal origin has been unclear. Two mechanisms have been proposed: conjunctive grid × direction cells aligned to the grid axes, and firing rate adaptation when grid fields are visited in quick succession.

Across almost 4,000 rat grid cells, conjunctive cells' directional tuning was broad and not aligned with the grid axes. Firing, by contrast, was reduced for about a second after grid field visits, consistent with adaptation. Simulations of realistic grid cell populations show that adaptation produces HexMod with the relatively straight trajectories of human experiments, and quantify how it depends on grid scale, adaptation time constant and movement speed. The work gives a framework for relating human neuroimaging to neuronal activity.

{% assign hexmod = site.data.publications | where: "id", "reggio2026hexmod" %}
{% for pub in hexmod %}{% include publication.html pub=pub %}{% endfor %}

The rat recordings from Barry et al. (2012) and Ólafsdóttir et al. (2016) analysed in this work are openly available on [Zenodo](https://doi.org/10.5281/zenodo.23477461). The analysis and simulation code will be released alongside the preprint.

## Collaborators

Misun Kim, Zilong Ji and Neil Burgess (UCL Institute of Cognitive Neuroscience), Daniel Bush (UCL Neuroscience, Physiology &amp; Pharmacology), and Caswell Barry (UCL Cell &amp; Developmental Biology).
