---
layout: single
permalink: /about/
title: "About us"
---


The creation of the **Bloom Perf Project** :rosette: stems from the collective experience of its founders in managing complex IT
projects, implementing information system architectures, and software development. Faced with specific challenges in
performance testing, the team developed original and practical methods, revealing a shared need in the IT community
for such resources.


The primary goal of the **Bloom Perf Project** is to provide performance testing tools that are both powerful and easy to
use. The project aims to facilitate access to these resources and to promote a rich exchange around best practices in
this area.


The ambition of the **Bloom Perf Project** is to establish a reference community and a set of resources for professionals
interested in performance testing, emphasizing the importance of specialized skills in this sector.


The project is carried by a team of engineers with extensive experience in development, project management, and
information system architecture. This collective expertise forms the foundation of the project.


The **Bloom Perf Project** offers tools such as injectors and mocks, designed to be effective, reliable, and easily
configurable. These tools have been validated in production environments and are intended to cover a wide range of
applications.


The **Bloom Perf Project** is an open space for all those who wish to explore, learn, and contribute to the evolution of
performance testing in the IT world. The team encourages collaboration and sharing of experiences to enrich and
diversify the available resources.

### Contributors

<div style="text-align: center;">
  {% for contributor in site.github.contributors %}
    <div style="display: inline-block; text-align: center; margin: 10px;">
      <a href="{{ contributor.html_url }}">
        <img src="{{ contributor.avatar_url }}" alt="{{ contributor.login }}" style="width: 100px; height: 100px; border-radius: 50%;" />
        <p style="margin-top: 5px; text-align: center;"><a href="{{ contributor.html_url }}">{{ contributor.login }}</a></p>
      </a>
    </div>
  {% endfor %}
</div>