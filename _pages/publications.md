---
layout: page
permalink: /publications/
title: publications
description: 
years: [2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

Only key publications are listed here. The full list can be found in my [DBLP](https://dblp.org/pid/154/4313.html).

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>