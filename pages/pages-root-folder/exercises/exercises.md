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
{% for exercise in site.data.exercises %}
  {% for page in site.pages %}
    {% if exercise.module == page.module and page.categories contains 'hasexercises' %}
      <h2><a href="{{ site.url }}{{ site.baseurl }}/exercises/{{ exercise.id }}/">{{ exercise.id }}. {{ exercise.title }}</a></h2>
      <h5>{{page.lesson}}</h5>
      <h4><a href="{{ site.url }}{{ site.baseurl }}{{ page.permalink }}/">{{ page.title }}</a></h4>
    {% endif %}
  {% endfor %}
{% endfor %}
</div>
