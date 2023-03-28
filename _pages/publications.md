---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Full publication list is given below. Please see <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a> for bibliometrics.

<!-- ## To Appear -->
## To Appear

{% include publications.html year="to appear" %}

{% for yr in (2010..2023) reversed %}
## {{yr}}
{% include publications.html year=yr %}
{% endfor %}
