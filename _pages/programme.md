---
title: "Senses in Motion - Programme"
layout: gridlay
excerpt: "Symposium programme"
sitemap: false
permalink: /programme
---

# Draft programme

<div class="row">
<div class="col-sm-12">
<p></p>
<table class="table table-hover">
  <thead>
    <tr>
      <th scope="col" style="width: 130px">Time</th>
      <th scope="col">Speaker</th>
      <th scope="col">Title</th>
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
      <td>{% unless session.break %}{{ session.name }}{% endunless %}</td>
      <td>
      {% if session.break %}
      {{ session.name }}
      {% else %}
      <a href="{{ site.url }}{{ site.baseurl }}/speakers#{{ session.name }}">{{ session.title }}</a>
      {% endif %}
      </td>
    </tr>
    {% endfor %}
  </tbody>
</table>
</div>
</div>
