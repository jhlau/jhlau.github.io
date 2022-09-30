---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% for yr in (2019..2022) reversed %}
## {{yr}}
{% include teaching.html year=yr %}
{% endfor %}
