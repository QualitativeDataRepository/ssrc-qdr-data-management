---
layout: page-fullwidth
show_meta: false
title: "Modules"
breadcrumb: true
header: false
hidefooter: false
categories: [modules]
permalink: "/modules/"
image:
    title: /assets/img/splash.jpg
---
<div class="item">
  {% for page in site.pages %}
    {% if page.categories contains 'moduleoverviews' %}
      <h3><a href="{{ site.url }}{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></h3>
      <p>{{page.description}}</p>  
    {% endif %}
  {% endfor %}
</div>