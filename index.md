---
redirect_from:
  - /home
---

# Welcome to the Yao-Cheng Lab

**Bioinformatics & Computational Genomics Group**

The Bioinformatics and Computational Genomics group consists of a multidisciplinary team of researchers with backgrounds in biology, computer science, mathematics, and statistics.
The lab members work collaboratively on different aspects of plant genomics and bioinformatics and also participate in international consortia and networks.
The lab has established collaborations with leading researchers from Taiwan and other countries.

If you are interested in joining Dr. Lin's lab or collaborating with him, please feel free to contact him by email at yalin AT sinica.edu.tw.

{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% include section.html %}

## Tools

{% include list.html component="card" data="projects" filter="home == true" %}

{%
  include button.html
  link="resources"
  text="All tools, data & facilities"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Highlights

{% capture text %}

We study the molecular mechanisms and evolutionary forces that shape plant genome diversity and adaptation, from comparative genomics to crop stress biology and plant phenotyping.

{%
  include button.html
  link="research"
  text="Our research and publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research/comparative-genomics.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Biologists, computer scientists, statisticians, and plant tamers working together at the Academia Sinica Southern Campus in Tainan.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/news/2025-07-01-welcome-2025-summer-interns.jpg"
  link="team"
  title="Our Team"
  flip=true
  text=text
%}

{% include section.html %}

## Latest news

{% for post in site.posts limit: 3 %}
  {%
    include post-excerpt.html
    url=post.url
    title=post.title
    image=post.image
    date=post.date
    tags=post.tags
    content=post.content
    excerpt=post.excerpt
  %}
{% endfor %}

{%
  include button.html
  link="news"
  text="All news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
