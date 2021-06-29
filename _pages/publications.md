---
layout: page
permalink: /publications/
title: publications & preprints
description: My publications & preprints
years: [2019, 2020]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
