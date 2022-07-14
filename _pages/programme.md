---
title: "Senses in Motion - Programme"
layout: gridlay
excerpt: "Symposium programme"
sitemap: false
permalink: /programme
---
# Symposium programme
<div class="row">
<div class="col-sm-12">

<table class="table table-hover">
  <thead>
    <tr>
      <th scope="col">Time</th>
      <th scope="col">Speaker</th>
      <th scope="col">Title</th>
    </tr>
  </thead>
  <tbody>
    {% for speaker in site.data.speakers %}
    <tr>
      <th scope="row">{{ speaker.time }}</th>
      <td>{{ speaker.name }}</td>
      <td><a href="{{ site.url }}{{ site.baseurl }}/speakers#{{ speaker.name }}">{{ speaker.title }}</a></td>
    </tr>
    {% endfor %}
  </tbody>
</table>
</div>
</div>
