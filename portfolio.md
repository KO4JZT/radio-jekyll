---
layout: page
title: Portfolio
permalink: /portfolio/
updated: 3-14-2021
---

{% assign projects = site.portfolio | sort: 'date' | reverse %}
{% for project in projects %}
  <a href='{{ project.url }}'>
    <img src='{{ project.image }}'>
  </a>
{% endfor %}