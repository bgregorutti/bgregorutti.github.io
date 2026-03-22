---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Research output from my time at **Safety Line** (2011–2020), in collaboration with INRIA, LIP6 (Sorbonne), and IFSTTAR. All work is grounded in real flight data and aviation applications.

{% include base_path %}

{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% for post in sorted_pubs %}
  {% include archive-single.html %}
{% endfor %}
