---
layout: default
title: Staff
---
<div class="row">
  {% for item in site.data.staff %}
    <div class="col-12 col-md-6 col-lg-4 card-box">
      <div class="card" style="width: 18rem;">
        <img src="assets/images/{{ item.photo }}" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">{{ item.name }}</h5>
          <p class="card-text">{{ item.nickname }}</p>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
