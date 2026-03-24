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
<div style="margin-bottom: 2em;">
  <strong>{{ post.title }}</strong><br>
  <em>{{ post.venue }}</em> &mdash; {{ post.date | date: "%Y" }}<br>
  {{ post.content }}
  {% if post.paperurl and post.paperurl != "" %}
  <a href="{{ post.paperurl }}" target="_blank">Download / View</a>
  {% endif %}
</div>
{% endfor %}
