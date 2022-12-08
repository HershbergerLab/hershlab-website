---
title: Home
---

# Vegetable Breeding & Genetics at Clemson University

{% include figure.html image="images/home/banner_butter_beans.png" width="100%" %}

{% include section.html %}

# Highlights

{% capture text %}
We strive to share our research with the broader scientific community, prioritizing transparency, rigor, and reproducibility.

{%
  include link.html
  link="publications"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research/sweetcornplot.png"
  link="publications"
  title="Our publications"
  text=text
%}

{% capture text %}
We are working to characterize, understand, and improve nutritional quality and flavor in vegetables. So far, our focus is on butter beans and sweet corn.

{%
  include link.html
  link="research"
  text="Vegetable research and breeding"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/seedling.JPG"
  link="research"
  title="Our Research"
  flip=true
  text=text
%}

{% capture text %}
We will soon be hiring a postdoctoral scholar to start in spring, 2023. Find descriptions and applications links on our [Team page](team).

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/planting_lunatus.jpg"
  link="team"
  title="Join us!"
  text=text
%}
