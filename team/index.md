---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The SeDIS Lab brings together a diverse team of researchers and students passionate about advancing the safety, security, and dependability of intelligent systems. Our team combines expertise in formal methods, artificial intelligence, cybersecurity, and cyber-physical systems to tackle challenging research problems through collaboration and innovation. We foster an inclusive and supportive research environment that encourages creativity, critical thinking, and professional growth while preparing the next generation of researchers and engineers.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

Graduate Students

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include list.html data="members" component="portrait" filter="role == 'masters'" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
