---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign gsShieldUrl = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class="anchor" id="about-me"></span>

# About Me

Zekun Chen received the B.Eng. degree in Electronic Information Engineering from Fujian Jiangxia University, Fuzhou, China, in 2015, the M.Eng. degree in Communication and Information Systems from Fujian Normal University, Fuzhou, China, in 2020, and the Ph.D. degree in Applied Physics from Northeast Normal University, Changchun, China, in 2025.

He is currently a Postdoctoral Researcher with the School of Physics, Northeast Normal University. His research interests include electrical impedance tomography, image processing, machine learning and deep learning.

For an up-to-date publication record, please see [Google Scholar](https://scholar.google.de/citations?user=dFJl65IAAAAJ). Total citations: **<span id="total_cit">--</span>**.

<span class="anchor" id="research"></span>

# Research Interests

- Electrical impedance tomography (EIT), including image reconstruction and inverse problems
- Image processing and computational imaging
- Machine learning and deep learning for sensing and imaging

<span class="anchor" id="education"></span>

# Education & Academic Position

- **2025.08 – Present**, Postdoctoral Researcher, School of Physics, Northeast Normal University, Changchun, China.

- **2021.09 – 2025.06**, Ph.D. in Applied Physics, School of Physics, Northeast Normal University, Changchun, China.  
  Supervisor: Prof. Shili Liang.

- **2017.09 – 2020.06**, M.Eng. in Communication and Information Systems, Fujian Normal University, Fuzhou, China.  
  Supervisor: Assoc. Prof. Rongtai Cai.

- **2011.09 – 2015.06**, B.Eng. in Electronic Information Engineering, Fujian Jiangxia University, Fuzhou, China.

<span class="anchor" id="publications"></span>

# Publications

{% include publications.html lang="en" %}
