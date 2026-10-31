---
title: Publications
nav:
  order: 2
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-scroll" %}Publications

Papers from the lab of Yao-Cheng Lin, generated automatically from his [ORCID](https://orcid.org/0000-0002-9390-795X) record and the list in `_data/sources.yaml`, refreshed every week.
Members' earlier work is listed on their [team pages]({{ "team" | relative_url }}).
See also Yao-Cheng Lin on [Google Scholar](https://scholar.google.com/citations?user=1d5qsg4AAAAJ&hl=en) and [ORCID](https://orcid.org/0000-0002-9390-795X).

{% include section.html %}

## Highlighted

{% include citation.html lookup="doi:10.1093/bioinformatics/btag781" style="rich" %}
{% include citation.html lookup="doi:10.1111/tpj.70452" style="rich" %}
{% include citation.html lookup="doi:10.1093/plphys/kiac022" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% comment %}lab papers: from the PI's ORCID (lab: true) or listed in _data/sources.yaml{% endcomment %}
{% include list.html data="citations" component="citation" style="rich" filter="lab == true or file == 'sources.yaml'" %}
