---
title: "Senses in Motion - Posters"
layout: gridlay
excerpt: "Posters"
sitemap: false
permalink: /posters
---

# Poster presentations

<div class="row">
  <ol>
  {% for poster in site.data.posters %}
  <li><a href="#{{ poster.name }}"><b>{{ poster.name }}</b>: {{ poster.title }}</a></li>
  {% endfor %}
  </ol>
  {% for poster in site.data.posters %}
  <div class="col-sm-12" id="{{ poster.name }}">
   <h3 style="text-align: left;">
  {{ poster.name }}: {{ poster.title }}
  </h3>
  <p>
  {{ poster.abstract }}
  </p>
  </div>
  {% endfor %}

</div>
