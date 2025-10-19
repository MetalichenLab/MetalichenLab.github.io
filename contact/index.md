---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our group is located in [SciLifeLab](https://www.scilifelab.se/) Campus Solna and affiliated with the [Department of Ecology, Environment and Plant Sciences](https://www.su.se/department-of-ecology-environment-and-plant-sciences/), at Stockholm University.

{%
  include button.html
  type="email"
  text="gulnara.tagirdzhanova@su.se"
  link="gulnara.tagirdzhanova [at] su.se"
%}
<!--{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}-->

{% include section.html %}

{% capture col1 %}
Visiting address:
Svante Arrhenius väg 20 A (or F)
114 18 Stockholm

Postal address:
Department of Ecology, Environment and Plant Sciences
Stockholm University
SE-106 91 Stockholm
Sweden
{%
  include figure.html
  image="images/scilife.jpg"
  caption="SciLifeLab, Solna"
%}

{% endcapture %}

{% capture col2 %}
Visiting address:
SciLifeLab
Tomtebodavägen 23A
17165 Solna, Sweden

Postal address:
SciLifeLab
Box 1031
17121 Solna, Sweden
{%
  include figure.html
  image="images/deep.jpg"
  caption="DEEP, Stockholm University"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

<!--{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %} -->
