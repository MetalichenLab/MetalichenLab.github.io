---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Current lab members


{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'researcher' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'intern' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'assistant' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'MSc' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'visitor' and group == 'current'" %}

{% include section.html %}

## Funders

{% capture content %}

[![SciLifeLab](/images/funders/scilife_logo.png)](https://www.scilifelab.se/research/#fellows)
[![Kungl. Fysiografiska Sällskapet i Lund](/images/funders/fysiografen.png)](https://www.fysiografen.se/en/)
[![The Lars Hierta Memorial Foundation](/images/funders/lars-hiertas-minne-logo.png)](https://www.larshiertasminne.se/)

{% endcapture %}

{% include grid.html  content=content %}


