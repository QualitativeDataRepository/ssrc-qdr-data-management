---
layout: page-fullwidth
show_meta: false
title: "Exercises"
breadcrumb: true
header: false
hidefooter: false
categories: [exercises]
permalink: "/exercises/"
image:
    title: /assets/img/Cramblit-panorama.jpg
---
<div class="item">
{% for page in site.pages %}
  {% if page.categories contains 'modulecontent' %}
    <h2><a href="{{ site.url }}{{ site.baseurl }}{{ page.permalink }}">{{ page.title }}</a></h2>
    <h3>{{page.lesson}}</h3>
    {% for exercise in site.data.exercises %}
      {% if exercise.module == page.module %}
        <h4><a href="{{ site.url }}{{ site.baseurl }}/exercises/{{ exercise.id }}/">{{ exercise.title }}</a></h4>
        <p>{{exercise.description}}</p>  
      {% endif %}
    {% endfor %}
  {% endif %}
{% endfor %}
</div>
