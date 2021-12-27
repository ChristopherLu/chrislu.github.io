---
layout: page
permalink: /publications/
title: publications
description: key publications in reversed chronological order. Full list in [DBLP](https://dblp.org/pid/154/4313.html)
years: [2021, 2020, 2019, 2018, 2017]
nav: true
---

<div class="publications">

<h2 class="year">preprints</h2>
{% bibliography -f papers -q @*[preprint=true]* %}

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}} && preprint!=true]* %}
{% endfor %}

</div>
