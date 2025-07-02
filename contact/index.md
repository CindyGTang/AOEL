---
title: Contact Us
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact Us

AOEL is based in the Department of Chemical and Biological Engineering (CBE) at the Hong Kong University of Science and Technology (HKUST). 

Our lab address is:

<a href="https://pathadvisor.ust.hk/from/to/7119;0HyuKKOTG_F;7;1448,334/floor/7/at/normalized/1448,334,3" target="_blank" class="ext su-link--external" data-extlink="">Room 7119</a>, 7/F (Lift 19),
Academic Building, HKUST,
Clear Water Bay Road
Kowloon, Hong Kong

Prof. Cindy Tang's office is located at <a href="https://pathadvisor.ust.hk/from/to/ROOM%204587/floor/4/at/normalized/2497,-214,3" target="_blank" class="ext su-link--external" data-extlink="" tooltip="location on HKUST pathadvisor for easy navigation">Room 4587</a>. 

{%
  include button.html
  type="email"
  text="cindytang@ust.hk"
  link="cindytang@ust.hk"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/aLSMiDidivJA8Uh57"
%}

{% include section.html %}

# {% include icon.html icon="fa-regular fa-envelope" %}Opportunities

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 col5=col5 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col4 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col5 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 col5=col5 %}
