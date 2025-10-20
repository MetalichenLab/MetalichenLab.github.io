---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Current lab members

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role == pi" %}
{% include list.html data="members" component="portrait" filters="role == researcher, group == current" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: current" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: current" %}
{% include list.html data="members" component="portrait" filters="role: bioinformatician, group: current" %}
{% include list.html data="members" component="portrait" filters="role: labtech, group: current" %}
{% include list.html data="members" component="portrait" filters="role: assistant, group: current" %}
{% include list.html data="members" component="portrait" filters="role: intern, group: current" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: current" %}
{% include list.html data="members" component="portrait" filters="role: guest, group: current" %}
{% include section.html background="images/banner.jpg" dark=true %}

{% include section.html background="images/header.jpg" dark=true %}

{% include section.html %}

## Funders

{% capture content %}

[![SciLifeLab](/images/scilife_logo.png)](https://www.scilifelab.se/research/#fellows)


{% endcapture %}

{% include grid.html  content=content %}


