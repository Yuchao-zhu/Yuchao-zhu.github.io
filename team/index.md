---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a dynamic team of chemists and biologists united in our mission to advance drug development. Our collaborative spirit drives us to integrate diverse expertise, fostering innovation and breakthroughs. We are passionate, dedicated, and driven by a shared commitment to making a meaningful impact in medicine. Together, we strive to overcome challenges and push the boundaries of what is possible in the pursuit of better health for all.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

Lab Alumni

{% include section.html %}

{% include section.html background="images/background.jpg" dark=true %}

At our lab, every member is a vital part of our journey. Join us to tackle challenging problems, celebrate achievements, and make lasting contributions to science.

{% include tags.html tags="join us" link="join" %}

{% include search-info.html %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/group-1.jpg" %}
{% include figure.html image="images/group-2.jpg" %}
{% include figure.html image="images/group-3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
