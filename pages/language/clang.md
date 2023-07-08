---
layout: page
show_meta: false
title: "C language"
#subheadline: "Database concept"
header: 
    image_fullwidth: "mediaplayer_js-title.jpg"
permalink: "/language/clang/"
---
<ul>
  {% for post in site.categories.clang %}
  <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url}}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
