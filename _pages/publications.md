---
layout: page
permalink: /publications/
title: Publications
subtitle: List of my publications. See also my <b><a href="https://scholar.google.fr/citations?hl=en&user=CyhIdmMAAAAJ">Google Scholare</a></b>.
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">
List of my publications. See also my <b><a href="https://scholar.google.fr/citations?hl=en&user=CyhIdmMAAAAJ">Google Scholar</a></b>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
