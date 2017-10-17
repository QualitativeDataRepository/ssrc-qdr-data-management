---
layout: page-fullwidth
show_meta: false
title: "Exercises"
breadcrumb: true
header: false
categories: [exercises]
permalink: "/exercises/"
image:
    title: /assets/img/splash.jpg
---
<div class="item">
  {% for exercise in site.data.exercises %}
    <h3><a href="{{ site.url }}{{ site.baseurl }}/exercises/{{ exercise.id }}/">{{ exercise.title }}</a></h3>
    <p>{{exercise.description}}</p>  
  {% endfor %}
</div>