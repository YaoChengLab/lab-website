---
title: Resources
nav:
  order: 5
  tooltip: Tools, data, and research platforms
---

# {% include icon.html icon="fa-solid fa-wrench" %}In science we share

At Academia Sinica, we host diverse research platforms designed to advance agricultural genomics research.
Leveraging our state-of-the-art infrastructure, we encourage collaborative initiatives aimed at broadening our understanding in critical areas, including genome evolution, plant-microbial and plant-environment interactions, tissue regeneration and engineering and crop breeding.
Furthermore, we explore the integration of computer vision and machine learning to foster versatile and sustainable agricultural production.

{% include section.html %}

## Tools & data

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{%
  include button.html
  link="resources/tools-data"
  text="All tools & datasets"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% include section.html %}

## Research platforms

{% include list.html component="card" data="projects" filter="group == 'platform'" %}

{% include section.html %}

## More software

{% include list.html component="card" data="projects" filter="!group" style="small" %}
