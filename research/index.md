---
title: Research
nav:
  order: 1
  tooltip: What we study
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Our current research aims to understand the molecular mechanisms and evolutionary forces that shape plant genome diversity and adaptation.
We use a combination of high-throughput sequencing technologies, computational methods, and experimental validation to study various aspects of plant genomics, including gene expression regulation, alternative splicing, transposable elements, epigenetics and horizontal gene transfer.

{% include section.html %}

{% capture text %}

We are generally interested in analyzing complex genomes to understand the changes and causes of genome structures, either driven by evolution, domestication, or engineering, including species in bacteria, fungi, diatoms, plants, and humans.
In addition to genome assembly, gene prediction, and comparative genome analysis, we are developing and incorporating new computational and genomic tools to analyze genomic information.
High-throughput sequencing data (Illumina, PacBio, and Oxford Nanopore) with chromosome conformation capture (Hi-C) data were frequently combined in our analysis to detect complex genome structures.

Tissue regeneration, genome engineering, and manipulation are routinely performed in functional studies, pharmaceutical production, and plant breeding.
However, the effect of these cellular stresses on genome stability remains unknown.
We developed a novel bioinformatics analysis using state-of-the-art sequencing methods to understand the somatic mutation spectrum, copy number variations, and abnormal chromosomal changes in human cell lines and polyploid plant genomes.
An in-house high-performance computing (HPC) cluster is the powerhouse for analyzing genomic data.

{% endcapture %}

{%
  include feature.html
  image="images/research/comparative_genomics.png"
  title="Comparative genomics"
  text=text
%}

{% capture text %}

A tightly regulated complex signal transduction network and chaperone machinery controls gene expression and enables the cell to change its transcriptional capacity within minutes in the presence of stress.
Multiple genes and regulatory networks have been identified that are involved in heat or flooding responses in different plants.
Plant reproductive development is particularly vulnerable to stressful conditions and causes substantial yield losses.
The goal of this research is to integrate association mapping and genomic selection to identify changes in gene expression levels, in particular alternative splicing (AS), allele specific expression (ASE) and transposable elements (TEs), which are involved in responses to abiotic stress.

{% endcapture %}

{%
  include feature.html
  image="images/research/crop-stress.jpg"
  title="Systems genetics of crop stress biology"
  flip=true
  text=text
%}

{% capture text %}

The imaging base, a non-invasive plant phenotyping system, can routinely measure plant phenotypes in a high-throughput manner.
However, the connections between plant phenotypes and internal phenotypic states, including cellular, tissue, and physiological properties, remain unclear.
Little information regarding the transcriptional, translational, and physiological states of plants can be obtained using the external phenotype.
We are currently developing a crop physiological phenotyping platform using a holistic multidimensional omic approach.
Machine vision with advanced statistics and machine learning frameworks will be developed to process imaging-based traits.
This will allow us to select imaging features that can act as a proxy for the underlying physiological processes.

{% endcapture %}

{%
  include feature.html
  image="images/research/phenotyping.jpg"
  title="Plant phenotyping"
  text=text
%}

{% include section.html %}

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
%}
