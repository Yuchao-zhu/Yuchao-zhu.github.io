---
---

# Innovating for a Healthier World

Our research group is dedicated to exploring the frontiers of biocompatible chemistry, genetic code expansion, and directed evolution, with the aim of enhancing drug discovery capacity and developing more effective therapies for human diseases by leveraging the insights and tools derived from our research.

{% include section.html %}

{% capture highlight_image %}
{%
  include image.html
  image="images/photo.jpg"  <!-- 替换为你想要插入的图片路径 -->
  alt="Highlight Image"
  style="full"
%}
{% endcapture %}

## Highlights

{% capture text %}

We use chemistry to answer important questions in biology and medicine. In all of our research, we prioritize transparency, rigor, and reproducibility.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Chemistry + Biology.png"
  link="research"
  title="Chemistry + Biology → insight"
  text=text
%}

{% capture text %}

 We focuses on advancing biocompatible chemistry, directed evolution, and enhancing drug discovery to pioneer innovative solutions for human health.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Biotechnology.png"
  link="projects"
  title="Frontiers of Biotechnology"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a team of enthusiastic researchers that want to push the frontier of chemistry and biology. We strive to build an inclusive environment for research, and recognize the value of diversity in the process of discovery.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.png"
  link="team"
  title="The next generation of medical scientists"
  text=text
%}
