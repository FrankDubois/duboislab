---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are always looking for enthusiastic new labmembers at several levels (PhD and MD students, postdocs or MSci students). 
If you are interested in studying how recurrent genomic rearrangements impact oncogene regulation in cancer 
and are passionate about biomedical research let us know! 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}



{% include section.html %}

We are grateful for research support from 
{% capture content %}

{% include figure.html image="images/DKH_Logo_RGB_640x360px_72dpi_Website.jpg" width="640px" %}
{% include figure.html image="images/Charite.jpg" width="640px" %}
{% include figure.html image= "images/BIH_logo.jpg" %}


{% endcapture %}

{% include grid.html style="100%" content=content %}
