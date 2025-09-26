---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find the full list of my works on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


# Publications

## 2025

<div style="display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start;">
  <div style="flex-shrink: 0;">
    <img src="paper-thumbnail-1.jpg" alt="Paper Thumbnail" style="width: 150px; height: 112px; border: 1px solid #ddd; border-radius: 6px; object-fit: cover;">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px;">From Prompt to Progression: Taming Video Diffusion Models for Seamless Attribute Transition </h3>
    <div style="margin-bottom: 6px;"><strong>Ling Lo</strong>, Kelvin C.K. Chan, Wen-Huang Cheng, Ming-Hsuan Yang</div>
    <div style="font-style: italic; color: #666; margin-bottom: 10px;"><em>ICCV 2025</em></div>
    <div><a href="link-to-pdf">Paper</a> | <a href="link-to-code">Code</a></div>
  </div>
</div>

---

<div style="display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start;">
  <div style="flex-shrink: 0;">
    <img src="paper-thumbnail-2.jpg" alt="Paper Thumbnail" style="width: 150px; height: 112px; border: 1px solid #ddd; border-radius: 6px; object-fit: cover;">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px;">Another Research Paper: Advancing the State of the Art</h3>
    <div style="margin-bottom: 6px;">Co-Author Name, <strong>Your Name</strong>, Third Author</div>
    <div style="font-style: italic; color: #666; margin-bottom: 10px;"><em>Journal Name 2025</em></div>
    <div><a href="link-to-pdf">PDF</a> | <a href="link-to-code">Code</a> | <a href="link-to-supplementary">Supplementary</a></div>
  </div>
</div>

---

## 2024

<div style="display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start;">
  <div style="flex-shrink: 0;">
    <img src="paper-thumbnail-3.jpg" alt="Paper Thumbnail" style="width: 150px; height: 112px; border: 1px solid #ddd; border-radius: 6px; object-fit: cover;">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px;">Previous Year Publication: Building on Solid Foundations 🎤 <strong>Oral Presentation</strong></h3>
    <div style="margin-bottom: 6px;"><strong>Your Name</strong>, Advisor Name, Collaborator Name</div>
    <div style="font-style: italic; color: #666; margin-bottom: 10px;"><em>Major Conference 2024</em></div>
    <div><a href="link-to-pdf">PDF</a> | <a href="link-to-video">Video</a> | <a href="link-to-slides">Slides</a></div>
  </div>
</div>

---

<div style="display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start;">
  <div style="flex-shrink: 0;">
    <img src="paper-thumbnail-4.jpg" alt="Paper Thumbnail" style="width: 150px; height: 112px; border: 1px solid #ddd; border-radius: 6px; object-fit: cover;">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px;">Workshop Paper: Early Stage Research Contributions</h3>
    <div style="margin-bottom: 6px;">First Author, <strong>Your Name</strong>, Last Author</div>
    <div style="font-style: italic; color: #666; margin-bottom: 10px;"><em>Workshop at Major Conference 2024</em></div>
    <div><a href="link-to-pdf">PDF</a> | <a href="link-to-poster">Poster</a></div>
  </div>
</div>

---

## 2023

<div style="display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start;">
  <div style="flex-shrink: 0;">
    <img src="paper-thumbnail-5.jpg" alt="Paper Thumbnail" style="width: 150px; height: 112px; border: 1px solid #ddd; border-radius: 6px; object-fit: cover;">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px;">Earlier Work: Foundation of Current Research Direction</h3>
    <div style="margin-bottom: 6px;"><strong>Your Name</strong>, Senior Collaborator, Research Group</div>
    <div style="font-style: italic; color: #666; margin-bottom: 10px;"><em>Specialized Conference 2023</em></div>
    <div><a href="link-to-pdf">PDF</a> | <a href="link-to-code">Code</a></div>
  </div>
</div>

---

## Template Instructions

**How to use this template:**

1. **Replace paper details**: Update titles, authors, venues with your actual publications
2. **Add thumbnails**: Replace `paper-thumbnail-X.jpg` with your actual paper images (150x112px recommended)
3. **Update links**: Replace all `link-to-*` placeholders with actual URLs
4. **Add awards**: Use emojis and bold text for awards:
   - 🏆 **Best Paper Award**
   - 🎤 **Oral Presentation** 
   - 🌟 **Outstanding Paper**
   - 📝 **Spotlight**
5. **Bold your name**: Use `**Your Name**` to highlight your authorship

**Paper Template Structure:**
```html
<div style="display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start;">
  <div style="flex-shrink: 0;">
    <img src="paper-thumbnail.jpg" alt="Paper Thumbnail" style="width: 150px; height: 112px; border: 1px solid #ddd; border-radius: 6px; object-fit: cover;">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px;">Paper Title Here</h3>
    <div style="margin-bottom: 6px;">Author List with <strong>Your Name</strong> in bold</div>
    <div style="font-style: italic; color: #666; margin-bottom: 10px;"><em>Venue Year</em></div>
    <div><a href="link">PDF</a> | <a href="link">Code</a> | <a href="link">Project</a></div>
  </div>
</div>
```
