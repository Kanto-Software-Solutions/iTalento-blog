---
layout: page
subheadline: "Tecnoloogía"
title: "Ofertas y Noticias Tecnologicas"
teaser: "Aquí encuentras todo el materia reciente como noticias, tutoriales y mucho más, que te ayudará a aprovechar al máximo tu talento!"
header:
   image_fullwidth: "unsplash_9.jpg"
permalink: "/headers/"
---
<ul>
    {% for post in site.categories.tech %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>