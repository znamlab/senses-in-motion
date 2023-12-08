---
title: "Senses in Motion - Speakers"
layout: gridlay
excerpt: "Speakers"
sitemap: false
permalink: /speakers
---

# Speakers

<div class="row">
  {% for speaker in site.data.speakers %}
  {% unless speaker.break %}
  <div class="col-sm-12">
  <p></p>
  <h2 id="{{ speaker.name }}">
  {{ speaker.name }}: {{ speaker.title }}
  </h2>
  <p>
  {% if speaker.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/speakers/{{ speaker.photo }}" style="width: 250px; float: right">
  {% endif %}
  {{ speaker.abstract }}
  </p>
  </div>
  {% endunless %}

{% endfor %}

</div>
