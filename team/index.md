---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our group (BioModSquad) strives to find creative solutions to challenging problems in therapeutic design, 
and we employ a crosscutting approach for developing computational tools that incorporates multi-scale 
biomolecular modeling, machine learning, and global optimization. Accordingly, we strive to build an 
environment where diverse perspectives and experiences are not only welcomed but sought after.

{%
  include figure.html
  image="images/biomodsquad_26oct23.jpg"
  width="100%"
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)(?!postdoc$)" %}

{% include section.html background="images/tmv_assemb.jpg" dark=true %}

Our team is regularly looking for new members to join our group that share our passion for computational 
therapeutic design, and if interested please reach out to Dr. K about current openings. 


{% include section.html %}

{% capture content %}

{% include figure.html image="images/emmanuel.jpg" %}
{% include figure.html image="images/group_photo_lab.jpg" %}
{% include figure.html image="images/fani.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
