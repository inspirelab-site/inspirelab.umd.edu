---
title: Team
nav:
  order: 2
  tooltip: About our team
---
# {% include icon.html icon="fa-solid fa-users" %}Team
We are an interdisciplinary team of researchers committed to innovative, rigorous, reproducible, and open science. We welcome students and trainees from diverse backgrounds, fostering mutual learning and collaboration. Our core values emphasize upholding equitable guidelines to ensure fairness and inclusion for all team members.

## Principal Investigator
{% capture floatcontent %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% endcapture %}

{% include float.html content=floatcontent %}
{% assign member = site.members | where: "slug", "nan-xu" | first %}
Dr. Nan Xu is an incoming Assistant Professor (Jan 2025) at the [​Fischell Department of Bioengineering](https://bioe.umd.edu) at the University of Maryland, College Park. She is also affiliated to the [Program in Neuroscience & Cognitive Science](https://nacs.umd.edu). Nan directs Imaging- and Neuro-computations for Precision Informatics Research (INSPIRE) Lab. With a strong foundation as a computational scientist, her research spans statistical learning, applied mathematics, neuroscience, and various biomedical applications. Her primary efforts are centered on developing advanced computational models and analyses with functional neuroimaging data to uncover novel insights into brain functions and diseases. 

Nan completed her undergraduate studies at the University of Rochester, earning a B.S. in Electrical and Computer Engineering and a B.A. in Mathematics, with a minor in Music, in 2011. She then pursued graduate studies at Cornell University, where she received her M.Sc. (2015) and Ph.D. (2017) in Electrical and Computer Engineering, minoring in Applied Mathematics and Cognitive Neuroscience. Throughout her postdoctoral journey, Nan gained extensive interdisciplinary research experience, including a fellowship in Chemical and Biomolecular Engineering at Georgia Tech (2017-2018), a visiting scientist role at the McGovern Brain Institute at MIT (2022), and a postdoctoral fellowship in Biomedical Engineering at Georgia Tech and Emory University (2019-2024). Her research is currently supported by a NIH BRAIN K99/R00 award. <a href="/members/nan-xu.html">[Learn more...]</a>

{% include section.html%}
## Openings!
{% include list.html data="members" component="portrait" filters="role: programmer" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html background="images/background.jpg" dark=true %}
## Collaborators
INSPIRE Lab benefits from our talented collaborators from diverse fields around the world.
- Keilholz MIND Lab @ Gatech-Emory, BME
- Chuang's Lab @ Queensland Brain Institute
- Dr. Evelyn Lake group @ Yale School of Medicine, Radiology & Biomedical Imaging
- Small Animal MR Facility @ University of Maryland, Brain and Behavior Institute
- Center for Translational Research in Neuroimaging and Data Science
- Dr. Jason Allen Group @ Indiana University Medical School, Radiology & Imaging Science; Emory Med School, Radiology
- Dr. Rupa Radhakrishnan Group @ Indiana University Medical School, Radiology & Imaging Science
- Dr. Ellen Schur Group @ University of Washington Medicine Diabetes Institute 
- CoNTRoL Lab @ Gatech, Psychology
- Attention & Working Memory Lab @ Gatech, Psychology
- Lab of Brain and Cognition @ McGill University, Neurology and Neurosurgery
- Doerschuk Lab @ Cornell, ECE, BME
- Dr. Dan Barbasch Group @ Cornell, Mathematics
- Dr. John E Johnson Group @ Scripps Research Institute, Structural Virology
- The Veesler Lab @ University of Washington, Biochemistry 

{% include section.html %}
## Funding
{% capture content %}
[![NIH Brain](/images/funders/nih-brain2.jpeg)](https://braininitiative.nih.gov/)

[![UMD BioE](/images/funders/umd-bioe.png)](https://bioe.umd.edu/)
{% endcapture %}
{% include grid.html style="cover" content=content %}