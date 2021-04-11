---
layout: page
title: Faculty
permalink: /faculty
ref: faculty
order: 2
---

{% for person in site.faculty %}

<img src="{{ person.url }}/300h.jpg" alt="thumbnail" align="left" style="margin-right:50px">
# {{person.name}}

{{person.content}}

----

{% endfor %}