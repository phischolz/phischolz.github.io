---
layout: default
title: Publications
nav_order: 2
---
My Publications

{% for p in site.data.publications %}
- {{ p.authors }} ({{ p.year }}). **{{ p.title }}**. {{ p.venue }}. [link]({{ p.link }})
{% endfor %}
