---
layout: page
show_meta: false
title: "Lab members!"
subheadline: "The ecosystem of the group"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/people/"
---
<ul>
    {% for post in site.categories.people %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>



<!--[Alumni!](/alumni/)-->

### Alumni

2018

* Vaibhvi Malhotra (rotation student, now at the University of Kiel)

2017

* Walter Veit (Bachelors project, University of Bayreuth)

<!-- &
[Collaborators!](/collaborators/) -->
