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

<h2 style="text-align: center; font-size: 40px; font-weight: 600; color: white;">
  Graduate Students
</h2>

{% include section.html %}

{% capture content %}

{% include portrait.html lookup="paapa-quansah" %}
{% include portrait.html lookup="mo" %}
{% include portrait.html lookup="abena-anning" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
