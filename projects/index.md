---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

The SeDIS Lab conducts research at the intersection of formal methods, artificial intelligence, and cybersecurity with the aim of bridging the gap between intelligent system capabilities and their dependable operation in real-world environments, with applications in robotics, autonomous systems, connected infrastructure, and other safety-critical technologies.

<h3>Research Projects</h3>
<p> Here are some projects that we are currently working on: </p>

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
