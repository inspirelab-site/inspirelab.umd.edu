---
title: Research
nav:
  order: 1
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research
We work in the interphase of data science and brain science, aiming to uncover brain function and cognitive mechanisms by modeling and analyzing the spatiotemporal brain dynamics. By employing multimodal functional neuroimaging data (e.g., fMRI-BOLD, LFP, optical imaging, MEG, etc.) from animals, humans, and patients, we decode complex processes shaping brain function and disease. This approach yields innovative insights for both fundamental and translational brain science. Welcome to explore our research themes:
* [Modeling and Inferences in Causal Interactions among Brain Networks](#section-1) 
* [Investigating Spatiotemporal Brain Dynamics across Species ](#section-2)
* [Assessing Functional Brain Dynamics in Neurological Disorders](#section-3)
* [3D Reconstruction from Cryo-EM: Statistical Characterization of Virus Particles](#section-4)

<a name="section-1"></a>
{% include section.html %}
### Modeling and Inferences in Causal Interactions among Brain Networks
{% capture text %}
fMRI BOLD brain dynamics are sensitive indicators for brain disorders, but understanding altered brain causal interactions requires incorporating causal information. To address this, we develop methods to model dynamic causal interactions, enhancing traditional correlation analysis by identifying the directionality of information flow and assessing whole-brain connectivity. These metrics reveal new insights into the spatiotemporal nature of cognitive functions, including memory consolidation. 
{% endcapture %}
<a name="section-2"></a>
{% include feature.html image="images/research/information-flow-diagram.png" link="https://doi.org/10.3389/fnins.2017.00271" flip=false  style="bare"  text=text%}


### Investigating Spatiotemporal Brain Dynamics across Species 
{% capture text %}
We develop novel analytical methods to investigate spontaneous fluctuations in blood oxygen level-dependent (BOLD) signals measured by fMRI. Using rodent models, we study the neuronal processes behind these fluctuations and translate our findings to human studies, focusing on similarities and differences in brain function and anatomy. Additionally, we explore how these dynamic processes respond to various cognitive tasks in humans.
{% endcapture %}
<a name="section-3"></a>
{% include feature.html image="images/research/cross-species.png"  link="https://doi.org/10.3389/fnins.2022.816331" flip=true  style="square"  text=text%}

### Assessing Functional Brain Dynamics in Neurological Disorders
{% capture text %} In collaboration with our clinical partners, we develop innovative analyses to assess functional brain dynamics in various neurological disorders measured by functional neuroimaging data. Specifically, we quantify the spatiotemporal dynamic processes in functional brain systems to decipher the neuropathophysiology of brain diseases such as post-concussive syndrome, obesity, and prenatal opioid exposure.{% endcapture %}
{% include feature.html image="images/research/information-flow-brain.png"  flip=false  style="bare"  text=text%}

<a name="section-4"></a>

### 3D Reconstruction from Cryo-EM: Statistical Characterization of Virus Particles
{% capture text %}
Cryo-electron microscopy (cryo-EM) provides essential 2D projection images of nano-scale bio-particles like viruses for understanding their biological function. Unlike traditional methods that assume strict geometric symmetry, we adopted a more realistic approach, allowing for individual particle asymmetry while maintaining overall mean and covariance symmetry. This novel method eliminated long-standing distortions in 3D reconstructions. Collaborating with virologists from the Scripps Institute, we uncovered allosteric effects along the symmetry axes of bacteriophage HK97. This algorithm can be applicable to most spherical virus particles with icosahedral and octahedral symmetries.
{% endcapture %}
{% include feature.html image="images/research/virus-recon.png" link="https://doi.org/10.1016/j.jsb.2017.12.013" flip=true style="bare" text=text %}