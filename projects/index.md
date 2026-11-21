---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

The SeDIS Lab conducts research at the intersection of formal methods, artificial intelligence, and cybersecurity with the aim of bridging the gap between intelligent system capabilities and their dependable operation in real-world environments, with applications in robotics, autonomous systems, connected infrastructure, and other safety-critical technologies. Here are some projects that we are currently working on.

<!--
<h3>Research Projects</h3>
<p> Here are some projects that we are currently working on: </p>
{% include tags.html tags="publication, resource, website" %}
{% include search-info.html %}
{% include section.html %}
-->

## Formal assurance of Learning-Enabled Autonomous Systems
<img
  src="{{ '/images/carla_fm.png' | relative_url }}"
  alt="Formal methods for robotics and CPS"
  style="float: left; width: 40%; max-width: 450px; height: auto; margin: 0 25px 15px 0;"
/>

<p>
Learning-enabled autonomous systems increasingly rely on artificial intelligence and machine learning to perceive their environments, make decisions, and perform complex tasks. However, the unpredictable behavior of learned models, environmental uncertainties, and adversarial conditions make it difficult to guarantee their safety, security, and reliability using conventional testing methods.
</p>
<p>
This research develops formal methods and computational frameworks for specifying, verifying, and assuring the behavior of learning-enabled autonomous systems. We investigate temporal logic and hyperproperty-based techniques to capture safety, security, and performance requirements, including properties involving multiple system executions. Our work combines formal verification, runtime monitoring, and learning-based control to detect specification violations, assess system behavior, and support safe decision-making under uncertainty. The long-term goal is to establish rigorous assurance mechanisms that enable autonomous robots, intelligent vehicles, and other safety-critical cyber-physical systems to operate reliably under uncertainty and adversarial conditions.
</p>

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Security and Privacy of Distributed Edge Intelligence and Learning-Enabled Cyber-Physical Systems
<img
  src="{{ '/images/ioat_research.png' | relative_url }}"
  alt="Formal methods for robotics and CPS"
  style="float: left; width: 40%; max-width: 450px; height: auto; margin: 0 25px 15px 0;"
/>

<p>
The growing integration of artificial intelligence, edge computing, and networked devices is transforming how cyber-physical systems (CPS) collect, process, and exchange information. By distributing intelligence across connected devices, these systems can make decisions closer to where data is generated, reducing communication delays and dependence on centralized computing infrastructure. However, their distributed nature introduces significant security and privacy challenges, including unauthorized data access, malicious model updates, compromised edge devices, and vulnerabilities arising from communication and resource constraints.
</p>
<p>
This research develops security and privacy-preserving methods for distributed edge intelligence and learning-enabled cyber-physical systems. We investigate secure and decentralized computing architectures, privacy-preserving federated and continual learning, and mechanisms for detecting and mitigating malicious behavior in collaborative learning environments. Our work also examines how cyberattacks, compromised devices, and evolving operating conditions affect the reliability and performance of distributed intelligent systems.

The long-term goal is to enable secure, privacy-preserving, and resilient distributed intelligence that can support trustworthy decision-making in autonomous robots, connected vehicles, Internet of Things (IoT) networks, and other mission-critical cyber-physical systems.
</p>
{% include list.html component="card" data="projects" filter="!group" style="small" %}
