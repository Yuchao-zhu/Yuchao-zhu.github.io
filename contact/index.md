---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are seeking innovative and curious researchers to join our lab and collaborate on groundbreaking projects. Our initiatives include biocompatible chemistry, directed evolution, drug screening, and other cutting-edge research areas. We cordially invite researchers passionate about revolutionizing drug discovery and medical research to join us. Candidates with chemistry, biology, or computational sciences backgrounds are highly desirable. We are also open to highly motivated individuals who may not have prior research experience but demonstrate a strong drive to learn and contribute.

{%
  include button.html
  type="email"
  text="yuchaozhu@cimrbj.ac.cn"
  link="yuchaozhu@cimrbj.ac.cn"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
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
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
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
