---
layout: page
title: Pads
permalink: /pads/
edit: false
---

We use these pads for volatile information that is helpful
to hillhackers on the venue. We have the following pads listed:

### 2017

{% for pad in site.data.pads['2017'] %}
- [{{pad[0]}}](https://pads.hillhacks.in/{{pad[1]}})
{% endfor %}

### 2018

{% for pad in site.data.pads['2018'] %}
- [{{pad[0]}}](https://pads.hillhacks.in/{{pad[1]}})
{% endfor %}

You can add more pads by editing [this file][pads.yml] on GitHub.

[pads.yml]: https://github.com/hillhacks/website/blob/master/_data/pads.yml
