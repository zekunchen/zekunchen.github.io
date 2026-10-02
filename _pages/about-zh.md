---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
lang: zh
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign gsShieldUrl = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class="anchor" id="about-me"></span>

# 关于我

陈泽坤于2015年获得福建江夏学院电子信息工程专业工学学士学位，2020年获得福建师范大学通信与信息系统专业硕士学位，2025年获得东北师范大学应用物理专业博士学位。

目前，他在东北师范大学物理学院从事博士后研究工作。主要研究方向包括电阻抗成像、图像处理与机器学习。

完整且最新的论文与引用信息请参见 [Google Scholar](https://scholar.google.de/citations?user=dFJl65IAAAAJ)。总引用次数：**<span id="total_cit">--</span>**。

<span class="anchor" id="research"></span>

# 研究方向

- 电阻抗成像（EIT），包括图像重建与逆问题
- 图像处理与计算成像
- 面向传感与成像的机器学习和深度学习方法

<span class="anchor" id="education"></span>

# 教育与学术经历

- **2025.08 – 2027.08**，东北师范大学物理学院，博士后。  
  研究题目：*面向动态监测的电阻抗成像系统实现与应用*。

- **2021.09 – 2025.06**，东北师范大学物理学院，应用物理专业博士。  
  博士论文：*基于高空间分辨率的电阻抗成像研究*。  
  导师：梁士利教授。

- **2017.09 – 2020.06**，福建师范大学，通信与信息系统专业硕士。  
  硕士论文：*基于端点和曲率的轮廓表示及其应用研究*。  
  导师：蔡荣太副教授。

- **2011.09 – 2015.06**，福建江夏学院，电子信息工程专业本科。  
  毕业设计：*基于 MATLAB 的 FBG 数值模拟及其应用分析*。

<span class="anchor" id="publications"></span>

# 学术论文

{% include publications.html lang="zh" %}
