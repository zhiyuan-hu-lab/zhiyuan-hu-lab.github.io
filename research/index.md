---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research / 研究

We study single-cell and spatial omics, gene regulatory networks, and mechanisms of development and disease.

我们聚焦单细胞与空间多组学、基因调控网络，以及发育与疾病机制研究。

{% include section.html %}

## Highlighted

{% include citation.html lookup="doi:10.1101/2024.12.11.627935" style="rich" %}
{% include citation.html lookup="doi:10.1016/j.ccell.2020.01.003" style="rich" %}

{% include section.html %}

## All Publications / 全部论文

{% for citation in site.data.citations %}
  {% if citation.file == "sources.yaml" %}
    {% include citation.html citation=citation style="rich" %}
  {% endif %}
{% endfor %}
