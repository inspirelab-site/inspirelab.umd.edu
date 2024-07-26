---
Title: Home
---
# Welcome to INSPIRE Lab!
Imaging and Neuro-computations for Precision Informatics Research (INSPIRE) Lab, led by Dr. Nan Xu, is anchored at the intersection of data science and brain science. Our mission is to uncover brain function, neurological disorders, and other biological processes by developing novel data science approaches. Using multimodal functional neuroimaging data (e.g., fMRI-BOLD, LFP, optical imaging, MEG) from animals, humans, and patients, we decode complex brain processes and diseases, offering innovative insights for fundamental and translational brain science.
{% include section.html %}
## Highlights
{% include list.html data="posts" component="post-excerpt" lookup="2024-07-24"%}

{% capture text %}
We develop advanced data science approaches to interpret data from cutting-edge imaging techniques, providing novel insights for brain science, informatics, and beyond.
{%
  include button.html
  link="research"
  text="See our research themes"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{%
  include button.html
  link="papers"
  text="Publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="research/images/research.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %} 
We are an interdisciplinary team of researchers committed to innovative, rigorous, reproducible, and open science. We welcome students and trainees from diverse backgrounds, fostering mutual learning and collaboration. Our core values emphasize upholding equitable guidelines to ensure fairness and inclusion for all team members.
{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{%
  include button.html
  link="team/#openings"
  text="Join us!"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="team/images/team0.png"
  link="team"
  title="Our Team"
  text=text
%}

{% capture text %}
Explore our new repositories of data science software tools. Our code is completely open source, and we welcome contributions from the community. Join us to advance open science!
{%
  include button.html
  link="software"
  text="Browse our open software"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="software/images/software.jpg"
  title="Open Software"
  flip=true
  style="bare"
  text=text
%}
