---
layout: page
title: Portfolio
permalink: /portfolio/
updated: 2-20-2021
---

{% assign projects = site.portfolio | sort: 'date' | reverse %}
{% for project in projects %}
  <h3><a href="{{ project.url }}">{{ project.title }} - {{ project.date | date: "%b %Y" }}</a></h3>
{% endfor %}