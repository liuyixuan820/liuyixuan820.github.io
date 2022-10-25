---
layout: page
permalink: /publications/
title: Publications
description:
years: [2022]
nav: true
---

<div class="publications">
\* Denotes equal contributions.
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
