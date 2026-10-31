---
title: Data
permalink: /resources/data/
redirect_from:
  - /resources/tools-data/
---

# {% include icon.html icon="fa-solid fa-database" %}Data

Genomic data from our studies are publicly available for the scientific community, in line with the FAIR principles (Findable, Accessible, Interoperable, and Reusable).

{% include button.html icon="fa-solid fa-toolbox" text="Tools" link="resources/tools" %}
{% include button.html icon="fa-solid fa-microscope" text="Facilities" link="resources/facilities" %}

{% include section.html %}

<table>
  <thead>
    <tr>
      <th>Dataset</th>
      <th>Publication</th>
      <th>Accession</th>
      <th>Browse &amp; download</th>
    </tr>
  </thead>
  <tbody>
    {% for d in site.data.datasets %}
      <tr>
        <td>
          <strong>{{ d.name }}</strong><br>
          {{ d.organism | markdownify | remove: "<p>" | remove: "</p>" }}
        </td>
        <td>
          <a href="https://doi.org/{{ d.doi }}">{{ d.paper }}</a><br>
          <em>{{ d.journal }}</em>
        </td>
        <td>
          {% for a in d.accessions %}
            <a href="{{ a.link }}">{{ a.id }}</a>{% if a.note %} ({{ a.note }}){% endif %}<br>
          {% endfor %}
        </td>
        <td>
          {% for l in d.links %}
            <a href="{{ l.link }}">{{ l.text }}</a><br>
          {% endfor %}
        </td>
      </tr>
    {% endfor %}
  </tbody>
</table>
