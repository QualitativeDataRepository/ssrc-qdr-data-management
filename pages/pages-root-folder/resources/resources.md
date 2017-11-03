---
layout: page-fullwidth
show_meta: false
title: "resources"
breadcrumb: true
header: false
hidefooter: false
categories: [resources]
permalink: "/resources/"
image:
    title: /assets/img/splash.jpg
---
<div class="item">
  {% for page in site.pages %}
    {% if page.categories contains 'resourcecontent' %}
      <h3><a href="{{ site.url }}{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></h3>
      <p>{{page.description}}</p>  
    {% endif %}
  {% endfor %}
</div>