---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of [Auburn University](https://www.auburn.edu/)’s [Department of Chemical Engineering](https://www.eng.auburn.edu/chen/) in the [Samuel Ginn College of Engineering](https://www.eng.auburn.edu/). 

{%
  include button.html
  type="email"
  text="kieslich@auburn.edu"
  link="kieslich@auburn.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/UHssGqPs6NcDDr3a8"
%}

<video autoplay muted plays-inline class="welcome-video" style= "width: 100%;">
  <source src="images/around_ross_hall.mp4" type="video/mp4">
</video>

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/ross.jpg"
  caption="Ross Hall"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/atrium.jpg"
  caption="Ross Hall Atrium"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
