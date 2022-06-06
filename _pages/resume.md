---
layout: page
permalink: /resume/
title: resume
years: [2022]
nav: true
nav_order: 2
---

**GEOSPATIAL  ANALYST ∙ ENVIRONMENTAL GEOSCIENTIST**

* National recognition for analytical reports that saw theater strategic response altered at EUCOM level
* Constructed first searchable GEOINT database for Headquarters Air Force "ISR Flight Plan"
* Expertise in GIS, Python and R for spatiotemporal analysis and visualization
* Professional and academic experience in analysis and project leadership

<!-- _pages/resume.md -->
<div class="resume">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% history -f resume -q @*[year={{y}}]* %}
{% endfor %}

</div>
