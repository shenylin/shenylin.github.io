---
title: Research
permalink: /research/
weight: 1
---

<h1 class="mb-3">Research</h1>

<p class="mb-5">
  My research examines how people interpret and respond to information in technology-mediated environments.
</p>

<div class="row">
  {% for item in site.research %}
    <div class="col-md-6 mb-4">
      <a href="{{ item.url | relative_url }}" class="text-decoration-none text-body">
        <div class="card h-100">

          {% if item.image %}
            <img
              src="{{ item.image | relative_url }}"
              class="card-img-top"
              alt="{{ item.title }}"
              style="height: 220px; object-fit: cover;"
            >
          {% endif %}

          <div class="card-body">
            <h2 class="h4 card-title">{{ item.title }}</h2>
            <p class="card-text">{{ item.description }}</p>
          </div>

        </div>
      </a>
    </div>
  {% endfor %}
</div>
