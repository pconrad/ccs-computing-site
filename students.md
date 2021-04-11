---
layout: page
title: Students
permalink: /students
ref: students
order: 2
---


{% for person in site.students %}

<img src="{{site.baseurl}}{{person.url}}/50h.jpg" alt="thumbnail" align="left" style="margin-right: 30px">
<h2><a href="{{site.baseurl}}{{person.url}}">{{person.name}}</a> | Year {{person.year}}</h2>

{% endfor %}