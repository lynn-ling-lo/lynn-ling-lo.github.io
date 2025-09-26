---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

# Selected Publications

## 2025

### From Prompt to Progression
![Paper Thumbnail](paper-thumbnail-1.jpg)

**Your Name**, Co-Author Name, Another Author, Senior Author  
*Conference/Journal Name 2025*

[PDF](link-to-pdf) | [Code](link-to-code) | [Project](link-to-project) | [arXiv](link-to-arxiv)

---



{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
