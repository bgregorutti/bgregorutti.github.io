---
layout: single
title: "Research Projects"
permalink: /projects/
author_profile: true
---

These are the main data science and AI projects I led or contributed to at **SCAI – Sorbonne Center for Artificial Intelligence** (2023–present). Each project is a collaboration between SCAI's data science team and one or more research labs from Sorbonne University and its partners.

All projects involve close collaboration between my team and domain-expert researchers, with the goal of applying state-of-the-art ML methods to real scientific problems.

---

{% assign sorted_projects = site.projects | sort: 'order' %}
{% for project in sorted_projects %}
## [{{ project.title }}]({{ project.url }})

**Domain:** {{ project.domain }} · **Status:** {{ project.status }}

{{ project.excerpt }}

[→ Read more]({{ project.url }}){: .btn .btn--primary}

---
{% endfor %}
