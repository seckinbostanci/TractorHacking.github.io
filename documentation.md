---
layout: page
title: Documentation
permalink: /documentation/
---

Documentation of our efforts to reverse engineer the John Deere CAN bus protocol can be found here.  This project is a *work in progress* through March 2018.

<ul>
{% for item in site.documentation %}
  <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>

Documentation of individual CAN-BUS IDs extracted from the tractor can be found below:

<p style="text-indent:1em"><a href="/IdExplanation">CAN-Bus ID Format Explanation</a></p>

<ul>
{% for item in site.idinfo %}
  <li><a href="{{ item.url }}"><span style="font-family:monospace">{{ item.title }}</span> - {{item.description}}</a></li>
{% endfor %}
</ul>

