---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Located at <strong>CIMR, Beijing (10 Xitoutiao, Youanmen Wai, Fengtai District, Beijing 100069, China).</strong> 

{%
  include button.html
  type="email"
  text="yuchaozhu@cimrbj.ac.cn"
  link="yuchaozhu@cimrbj.ac.cn"
%}
{%
  include button.html
  type="phone"
  text="(000) 0000-0000"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/CMU-1.jpg"
  caption=""
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/CMU-2.jpg"
  caption=""
%}

{% endcapture %}

{%
  include figure.html
  image="images/CMU-3.jpg"
  caption=""
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

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

{% include cols.html col1=col1 col2=col2 col3=col3 %}
