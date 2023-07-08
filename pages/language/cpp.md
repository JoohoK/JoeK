---
layout: page
show_meta: false
title: "C++ language"
#subheadline: "Database concept"
header: 
    image_fullwidth: "mediaplayer_js-title.jpg"
permalink: "/language/cpp/"
---
<ul>
  {% for post in site.categories.cpp %}
  <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url}}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
