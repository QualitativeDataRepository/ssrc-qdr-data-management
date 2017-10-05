---
layout: page
show_meta: false
title: "Lessons"
breadcrumb: true
header: no
categories: [lessons]
permalink: "/lessons/"
---
<div class="item">
  {% for page in site.pages %}
    {% if page.categories contains 'lessonoverviews' %}
      <h3><a href="{{ site.url }}{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></h3>
      <p>{{page.description}}</p>  
    {% endif %}
  {% endfor %}
</div>