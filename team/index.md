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

{% include figure.html image="/images/funders/vr2.png" link="https://www.vr.se/english.html" %}
{% include figure.html image="/images/su_logo.png" link="https://www.su.se/english" %}
{% include figure.html image="/images/funders/fysiografen.png" link="https://www.fysiografen.se/en/" %}
{% include figure.html image="/images/funders/lars-hiertas-minne-logo.png" link="https://www.larshiertasminne.se/" %}



{% endcapture %}

{% include grid.html  content=content %}


