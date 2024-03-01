---
title: "Senses in Motion - Programme"
layout: gridlay
excerpt: "Symposium programme"
sitemap: false
permalink: /draft-programme
---

# Draft programme

<div class="row">
<div class="col-sm-12">
<p></p>
<table class="table table-hover">
  <thead class="thead-dark">
    <tr>
      <th scope="col" style="width: 130px">Time</th>
      <th scope="col" style="width: 130px">Location</th>
      <th scope="col">Session</th>
    </tr>

  </thead>
  <tbody>
    {% for session in site.data.programme %}
    {% if session.highlight %}
    <tr class="table-dark">
    {% else %}
    <tr>
    {% endif %}
      <th scope="row">{{ session.time }}</th>
      <td>{{ session.location }}</td>
      <td>{{ session.name }}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>
</div>
</div>
