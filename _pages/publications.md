---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order.
years: []
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
