---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% for yr in (2019..2026) reversed %}
## {{yr}}
{% include teaching.html year=yr %}
{% endfor %}
