---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Current lab members


{% include list.html data="members" component="portrait" filters="role == pi" %}
{% include list.html data="members" component="portrait" filters="role == postdoc and group == current" %}
{% include list.html data="members" component="portrait" filters="role == phd and group == current" %}

{% include section.html %}

## Funders

{% capture content %}

[![SciLifeLab](/images/scilife_logo.png)](https://www.scilifelab.se/research/#fellows)


{% endcapture %}

{% include grid.html  content=content %}


