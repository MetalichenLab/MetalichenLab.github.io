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
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/footer.jpg" dark=true %}

## Funders

{% include section.html %}

{% capture content %}

{% include figure.html image="images/SciLifeLab_Logo.svg" %}

{% endcapture %}

{% include grid.html  content=content %}


