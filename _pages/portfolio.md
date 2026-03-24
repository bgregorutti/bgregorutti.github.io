---
layout: archive
title: "Selected Projects"
permalink: /portfolio/
author_profile: true
---

These are the main data science and AI projects I led or contributed to at **SCAI** (2023–present), **LumenAI** and **Safety line**. Each project is a collaboration between SCAI's data science team and one or more research labs from Sorbonne University and its partners.

{% include base_path %}

{% assign sorted = site.portfolio | sort: 'order' %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}
