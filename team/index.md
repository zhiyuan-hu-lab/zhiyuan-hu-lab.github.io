---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team / 团队

Hu Lab is based at Wuhan University Medical Research Institute / Frontier Science Center for Immunology and Metabolism.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and group != 'alum'" %}

{% include section.html background="images/background.jpg" dark=true %}

We welcome motivated students and collaborators interested in single-cell and spatial omics, regulatory genomics, and development & disease.
