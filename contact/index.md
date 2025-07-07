---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# Contact

**_SWEET Research Group_** is with the College of Health at Lehigh University in Bethlehem, Pennsylvania. We always seek motivated undergraduate and graduate students to learn and conduct research with us, as well as collaborations for research and fun projects. 


_Reach out to Prof. Rui Hua (_**_ruh725@lehigh.edu_**_) for research opportunities, collaborations, or any inquires._ 


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
  caption="College of Health, Health, Science & Technology (HST) Building"
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
