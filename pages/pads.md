---
layout: page
title: Pads
permalink: /pads/
---

We have the following pads listed:

### 2017

{% for pad in site.data.pads['2017'] %}
- [{{pad[0]}}](https://pads.hillhacks.in/{{pad[1]}})
{% endfor %}