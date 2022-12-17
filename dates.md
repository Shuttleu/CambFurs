---
layout: default
title: Dates
---
# Meet Dates

The following dates are the currently planned.

<table class="table table-dark">
  <thead>
    <tr>
      <th scope="col">Date</th>
      <th scope="col">Discord/Inperson</th>
      <th scope="col">Special Notes</th>
    </tr>
  </thead>
  <tbody>
    {% for item in site.data.meets %}
      <tr>
        <th scope="row">{{ item.date }}</th>
        <td>{{ item.ip }}</td>
        <td>{{ item.notes }}</td>
      </tr>
    {% endfor %}
  </tbody>
</table>