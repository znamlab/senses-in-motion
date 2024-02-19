---
title: "Senses in Motion - Speakers"
layout: gridlay
excerpt: "Speakers"
sitemap: false
permalink: /speakers
---

# Speakers

<div class="row">
  {% assign sorted = site.data.speakers | sort: 'name'  %}
  {% for speaker in sorted %}
  {% unless speaker.break %}
  {% if speaker.title %}
  <div class="col-sm-12" id="{{ speaker.name }}">
  <h2>
  {{ speaker.name }}: {{ speaker.title }}
  </h2>
  <p>
  {% if speaker.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/speakers/{{ speaker.photo }}" style="width: 250px; float: right">
  {% endif %}
  {{ speaker.abstract }}
  </p>
  </div>
  {% endif %}
  {% endunless %}

{% endfor %}

</div>
