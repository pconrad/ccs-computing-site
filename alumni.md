---
layout: page
title: Alumni
permalink: /alumni
ref: alumni
order: 2
---


{% for person in site.alumni %}

<img src="{{site.baseurl}}{{person.url}}/50h.jpg" alt="thumbnail" align="left" style="margin-right: 30px">
<h2><a href="{{site.baseurl}}{{person.url}}">{{person.name}}</a> | {{person.affiliation}}</h2>

{% endfor %}