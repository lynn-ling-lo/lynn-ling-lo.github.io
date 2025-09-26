---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

# Selected Publications

## 2025

### From Prompt to Progression: Taming Video Diffusion Models for Seamless Attribute Transition
![Paper Thumbnail](paper-thumbnail-1.jpg)

**Ling Lo**, Kelvin C.K. Chan, Wen-Huang Cheng, Ming-Hsuan Yang 
*ICCV 2025*

[Paper](https://arxiv.org/abs/2509.19690) | [Code](https://github.com/lynn-ling-lo/Prompt2Progression)

---



{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
