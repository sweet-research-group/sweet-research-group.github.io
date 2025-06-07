---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

SWEET Research Group is with College of Health at Lehigh University in Bethlehem, PA. We always seek motivated undergraduate and graduate students to learn and conduct research with us, as well as collaborations for research and fun projects. Reach out to Dr. Rui Hua (ruh725@lehigh.edu) for research opportunities, collaborations, or any inquires. 

{%
  include button.html
  type="email"
  text="ruh725@lehigh.edu"
  link="ruh725@lehigh.edu"
%}
<!-- {%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%} -->
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/AERaHcdoJowJMH5r8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Lehigh.jpeg"
  caption="Lehigh University"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/HST2.jpg"
  caption="Health, Science & Technology (HST) Building"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% capture col2 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% capture col3 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
