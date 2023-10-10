---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are always looking to have talented and enthusiastic people join our team. We are based at the Institute of Pathology at the Charité – Universitätsmedizin Berlin Campus Mitte, able to take advantage of all the resources the Charité research environment offers. If you are interested, please contact us with your CV and a description of your interests.

{%
  include button.html
  type="email"
  text="frank.dubois@charite.de"
  link="frank.dubois@charite.de"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/CqGR2de1hHw9LHMP9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/institut-fuer-pathologie-charite-berlin.jpg"
  caption="The Pathology Institute"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/institut-location.jpg"
  caption="Our location"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Campus address: <br>
Virchowweg 15, 
10117 Berlin,
Germany
{% endcapture %}

{% capture col2 %}
Mail address: <br>
Institute of Pathology
Charité – Universitätsmedizin Berlin
Charitéplatz 1,
10117 Berlin
Germany
{% endcapture %}

{% capture col3 %}
Institute website: <br>
https://pathologie-ccm.charite.de/en/
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
