---
layout: page
show_meta: false
title: "Diseño"
subheadline: "Blog"
header:
   image_fullwidth: "header_roadmap_2.jpg"
permalink: "/design/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>