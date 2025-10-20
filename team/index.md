---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Current lab members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi', group == current" %}

{% include section.html background="images/header.jpg" dark=true %}

{% include section.html %}

## Funders

{% capture content %}

{% include figure.html image="images/scilife_logo.png" %}
[![SciLifeLab](scilife_logo.png)](https://www.scilifelab.se/research/#fellows)


{% endcapture %}

{% include grid.html  content=content %}


