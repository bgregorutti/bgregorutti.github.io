---
layout: archive
permalink: /portfolio/
author_profile: true
---

These are the main data science and AI projects I led or contributed to at **SCAI** (2023–present), **LumenAI** (2020-2022) and **Safety line** (2015-2020). 

{% include base_path %}

{% assign sorted = site.portfolio | sort: 'order' %}

# Safety Line

{% for post in sorted %}{% if post.company == "Safety Line" %}  {% include archive-single.html %}
{% endif %}{% endfor %}

# SCAI

Each project is a collaboration between SCAI's data science team and one or more research labs from Sorbonne University and its partners.

{% for post in sorted %}{% if post.company == "SCAI" %}  {% include archive-single.html %}
{% endif %}{% endfor %}

# LumenAI

{% for post in sorted %}{% if post.company == "LumenAI" %}  {% include archive-single.html %}
{% endif %}{% endfor %}
