---
layout: page
show_meta: false
title: "Exercises"
breadcrumb: true
header: no
categories: [exercises]
permalink: "/exercises/"
---
<div class="item">
  {% for exercise in site.exercises %}
    <h3><a href="{{ site.url }}{{ site.baseurl }}{{ exercise.url }}">{{ exercise.title }}</a></h3>
    <p>{{exercise.description}}</p>  
  {% endfor %}
</div>