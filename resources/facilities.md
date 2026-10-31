---
title: Facilities
permalink: /resources/facilities/
redirect_from:
  - /resources/genomics/
---

# {% include icon.html icon="fa-solid fa-microscope" %}Facilities

Research platforms at the Academia Sinica Southern Campus for genomics, phenotyping, and computing.
For access or collaboration, please contact Dr. Yao-Cheng Lin (yalin AT sinica.edu.tw, ext. 212).

{% include button.html icon="fa-solid fa-toolbox" text="Tools" link="resources/tools" %}
{% include button.html icon="fa-solid fa-database" text="Data" link="resources/data" %}

{% include section.html %}

{% include list.html component="card" data="facilities" %}

{% include section.html %}

## Genomics instruments

We host a comprehensive suite of genomic resources, primarily focused on high-throughput sequencing library preparation.

{% capture content %}

{% include figure.html image="images/resources/gridion.jpg" caption="[Oxford Nanopore GridION](https://nanoporetech.com/products/sequence/gridion): single-molecule long-read sequencing" %}
{% include figure.html image="images/resources/bioanalyzer.jpg" caption="[Agilent BioAnalyzer 2100](https://www.agilent.com/en/product/automated-electrophoresis/bioanalyzer-systems/bioanalyzer-instrument/2100-bioanalyzer-instrument-228250): DNA & RNA quality control (size, quantitation, integrity and purity)" %}
{% include figure.html image="images/resources/tapestation.jpg" caption="[Agilent TapeStation 4150](https://www.agilent.com/en/product/automated-electrophoresis/tapestation-systems/tapestation-instruments/4150-tapestation-system-297322): DNA & RNA quality control (1 to 16 samples per run)" %}
{% include figure.html image="images/resources/bluepippin.jpg" caption="[BluePippin](https://sagescience.com/products/bluepippin/): DNA size selection for next-gen sequencing, with pulsed-field (100 bp – 50 kb)" %}
{% include figure.html image="images/resources/covaris.jpg" caption="[Covaris S220](https://www.covaris.com/s220-focused-ultrasonicator-500217): focused-ultrasonicator DNA/RNA shearing for short-read sequencing, FFPE extraction, chromatin shearing, cell lysis" %}
{% include figure.html image="images/resources/genomics-lab.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
