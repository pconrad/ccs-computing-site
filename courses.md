---
layout: page
title: Course information
permalink: /courses
ref: courses
order: 2
---

{% for course in site.courses %}

## {{course.title}}

Offered: {{course.quarter}}

{{course.content}}

---

{% endfor %}