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

{% include section.html background="images/background.jpg" dark=true %}

Yuchao Zhu is an Assistant Investigator (研究员) at the Chinese Institutes for Medical Research (CIMR), Beijing. Zhu earned his B.Sc. in Pharmaceutical Sciences from Peking University. As a Graduate Research Fellow at School of Pharmaceutical Sciences of Peking University, Zhu developed efficient methods for synthesizing organic molecules and drug candidates under the guidance of Prof. Ning Jiao. After receiving his Ph.D. in 2019, he was awarded the fellowship of China National Postdoctoral Program for Innovative Talents (博新计划) and Peking University Boya Postdoctoral Fellowship (博雅博士后) and joined Prof. Peng R. Chen's lab at College of Chemistry at Peking University, where he focused on applying bioorthogonal cleavage chemistry and genetic code expansiton to manipulate protein functions in living cells. He moved to the CIMR in 2024, where his on-going research leverages the power of evolution to develop next-generation strategies for addressing global problems in chemistry, biotechnology and medicine. Zhu’s current research interests include developing biocompatibel chemistry; creating new-to-nature enzymes with directed evolution; and pioneering novel bioactive modalities to therapeutically intervene in diverse disease states.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
