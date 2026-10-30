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

<a href="https://www.vr.se/english.html" target="_blank">
  {% include figure.html image="/images/funders/vr2.png" %}
</a>

<a href="https://www.su.se/english" target="_blank">
  {% include figure.html image="/images/su_logo.png" %}
</a>

<a href="https://www.fysiografen.se/en/" target="_blank">
  {% include figure.html image="/images/funders/fysiografen.png" %}
</a>

<a href="https://www.larshiertasminne.se/" target="_blank">
  {% include figure.html image="/images/funders/lars-hiertas-minne-logo.png" %}
</a>


{% endcapture %}

{% include grid.html  content=content %}


