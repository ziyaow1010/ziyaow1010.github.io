---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m currently a third-year Ph.D. student in the Department of Electrical and Computer Engineering at the University of Maryland, College Park, advised by Prof. [Ang Li](https://www.ang-li.com/). Before that, I received my B.E. in Computer Engineering from Wuhan University. I worked as a research intern at IBM Research (2024 summer) and Sony AI (2025 summer) on the topic of collaborative and efficient foundation models.

I prefer simple, elegant approaches to improving the performance and efficiency of foundation models. I focus on developing advanced collaborative edge AI systems, with three priorities: performance, efficiency, and security.

**Selected Publications**

(* = equal contribution) 

{% include base_path %}
{% assign pubs = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}
