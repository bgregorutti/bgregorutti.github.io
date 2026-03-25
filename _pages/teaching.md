---
layout: archive
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Teaching has been a consistent thread throughout my position at SCAI — from courses in statistics and Python to AI literacy workshops for non-technical audiences.

## Key figures (2023–2026)

|  | Personal | Team (SCAI) |
|---|---|---|
| Training hours | 230+ | 400+ |
| Students | 300+ | 700+ |
| Courses | 10+ | 40+ |

{% assign sorted_teaching = site.teaching | sort: 'date' | reverse %}
{% for post in sorted_teaching %}
  {% include archive-single.html %}
{% endfor %}
