---
layout: page
permalink: /talks/
title: Talks
description: A list of my talks and presentations.
nav: true
nav_order: 5
---

## Conference Presentations

{% assign conference_talks = site.data.talks | where: "type", "Conference" %}
{% for talk in conference_talks %}
<div class="card mt-3">
  <div class="card-body">
    <h5 class="card-title">{{ talk.title }}</h5>
    <p class="card-text text-muted">{{ talk.event }} &nbsp;|&nbsp; {{ talk.date }} &nbsp;|&nbsp; {{ talk.location }}</p>
    <div>
      {% if talk.slides %}
      <a href="{{ talk.slides }}" target="_blank" class="btn btn-sm btn-outline-primary">Slides</a>
      {% endif %}
      {% if talk.video %}
      <a href="{{ talk.video }}" target="_blank" class="btn btn-sm btn-outline-danger">Video</a>
      {% endif %}
    </div>
  </div>
</div>
{% endfor %}

<br>

