---
layout: default
title: Research
nav_order: 2
---

{% for p in site.data.publications %}
- {{ p.authors }} ({{ p.year }}). **{{ p.title }}**. {{ p.venue }}. [link]({{ p.link }})
{% endfor %}
