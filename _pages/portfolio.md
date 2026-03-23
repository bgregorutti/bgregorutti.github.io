---
layout: archive
title: "Selected Research Projects at SCAI"
permalink: /portfolio/
author_profile: true
---

These are the main data science and AI projects I led or contributed to at **SCAI – Sorbonne Cluster for Artificial Intelligence** (2023–present). Each project is a collaboration between SCAI's data science team and one or more research labs from Sorbonne University and its partners.

{% include base_path %}

{% assign sorted = site.portfolio | sort: 'order' %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}
