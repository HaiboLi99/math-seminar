---
title: "Schedule"
layout: page
permalink: /schedule/
---

# Schedule

<div class="section-card">

<div class="schedule-table-wrapper" markdown="0">

<table class="schedule-table">
  <thead>
    <tr>
      <th>Speaker</th>
      <th>Date & Time</th>
      <th>Topic</th>
    </tr>
  </thead>
  <tbody>
    {% for seminar in site.data.seminars %}
    <tr>
      <td>{{ seminar.speaker }}</td>
      <td>{{ seminar.date }}<br>{{ seminar.time }}</td>
      <td>{{ seminar.title }}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>

</div>

</div>