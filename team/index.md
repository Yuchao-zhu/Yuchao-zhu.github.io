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

We are seeking innovative and curious researchers to join our lab and collaborate on groundbreaking projects. Our initiatives include biocompatible chemistry, directed evolution, drug screening, and other cutting-edge research areas. We cordially invite researchers passionate about revolutionizing drug discovery and medical research to explore oppotunities below. Candidates with chemistry, biology, or computational sciences backgrounds are highly desirable. We are also open to highly motivated individuals who may not have prior research experience but demonstrate a strong drive to learn and contribute.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/group-1.jpg" %}
{% include figure.html image="images/group-2.jpg" %}
{% include figure.html image="images/group-3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
