---
title: Team
nav:
  order: 3
  tooltip: About our team
---
# {% include icon.html icon="fa-solid fa-users" %}Team
We are an interdisciplinary team of researchers passionate about innovative, rigorous, and transparent science. We warmly welcome students and trainees from diverse backgrounds, fostering mutual respect and collaboration. We are committed to fairness and inclusion, ensuring that everyone feels supported and valued.

## Principal Investigator
{% capture floatcontent %}
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% endcapture %}

{% include float.html content=floatcontent flip=false %}
{% assign member = site.members | where: "slug", "nan-xu" | first %}
Dr. Nan Xu directs Imaging- and Neuro-computations for Precision Informatics Research (INSPIRE) Lab. With a strong foundation in computational science, her research spans statistical and machine learning, applied mathematics, neuroscience, and various biomedical applications. Her current work focuses on developing advanced computational models and analyses of functional neuroimaging data to gain new insights into brain function, neurological diseases, and broader informatics applications.

Nan earned a B.S. in Electrical and Computer Engineering and a B.A. in Mathematics from the University of Rochester in 2011. She completed her M.Sc. (2015) and Ph.D. (2017) in Electrical and Computer Engineering at Cornell University, with minors in both Applied Mathematics and Cognitive Neuroscience. Her interdisciplinary postdoctoral experience includes a fellowship in Chemical and Biomolecular Engineering at Georgia Tech (2017-2018), a visiting scientist position at the McGovern Brain Institute at MIT (2022), and a postdoctoral fellowship in Biomedical Engineering at Georgia Tech and Emory University (2019-2024). Her research is currently supported by an NIH BRAIN K99/R00 award. <a href="/members/nan-xu.html">[Learn more...]</a>

{% include section.html %}
## Team Members
{% include list.html data="members" component="portrait" filter="group == 'member' and role == 'manager'" %}
{% include list.html data="members" component="portrait" filter="group == 'member' and role == 'programmer'" %}
{% include list.html data="members" component="portrait" filter="group == 'member' and role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="group == 'member' and role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="group == 'member' and role == 'masters'" %}
{% include list.html data="members" component="portrait" filter="group == 'member' and role == 'undergrad'" %}

<div style="font-size: 1.75em;">
  {%
    include button.html
    link="alumni"
    text="View Alumni Page"
    icon="fa-solid fa-arrow-right"
    flip=false
    style="bare"
  %}
</div>

{% include section.html %}
## Collaborators
{% include list.html data="collaborators" component="portrait" filter="role == 'collaborator'" %}

{% include section.html %}
## Funding
{% capture content %}
[![NIH Brain](/images/funders/nih-brain2.jpeg)](https://braininitiative.nih.gov/)

[![UMD BioE](/images/funders/umd-bioe.png)](https://bioe.umd.edu/)

[![UMD BBI](/images/funders/umd-bbi-resized2.png)](https://bbi.umd.edu/)

[![Grand Challenges Grant](/images/funders/grand-challenges.jpg)](https://research.umd.edu/grand-challenges-grants)
{% endcapture %}
{% include grid.html style="cover" content=content %}
