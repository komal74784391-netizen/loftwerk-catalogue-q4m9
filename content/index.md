---
layout: default
title: Instruments
---

# Loftwerk Instruments

Open-hardware test and measurement instruments. Each entry links its released
design package and, where applicable, the community implementation of the
published reference design it adapts.

{% for instrument in site.instruments %}
- [{{ instrument.title }}]({{ instrument.url }})
{% endfor %}
