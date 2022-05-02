---
title: Home
---

# Coming soon to Clemson University

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
We are working to characterize, understand, and improve nutritional quality and flavor in vegetables. Stay tuned as we figure out *which* vegetables...

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
  image="images/home/carrot_flower.jpeg"
  link="research"
  title="Our Research"
  flip=true
  text=text
%}

{% capture text %}
We're currently hiring graduate students and a technician. Find descriptions and applications links on our [Team page](team).

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
  image="images/photo.jpg"
  link="team"
  title="Join us!"
  text=text
%}
