---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% for yr in (2019..2020) reversed %}
## {{yr}}
{% include teaching.html year=yr %}
{% include publications.html year=yr %}
{% endfor %}
