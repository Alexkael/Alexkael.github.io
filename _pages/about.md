---
permalink: /
title: "Gaojie's Homepage"
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
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Gaojie is a final year PhD student in computer science at university of Liverpool, under the advisory of [Prof. Xiaowei Huang](https://cgi.csc.liv.ac.uk/~xiaowei/) and [Dr. Xinping Yi](https://sites.google.com/site/xinpingyi00/).

His research focuses on developing efficient, reliable algorithms (generalization, robustness, privacy, interpretability, etc) for modern machine learning models and applications, with formal theoretical guarantees and analyses. He is also interested in applying machine learning techniques to vision and financial applications.

# Publications 

- [Weight Expansion: A New Perspective on Dropout and Generalization](https://openreview.net/forum?id=w3z3sN1b04), TMLR
  **Gaojie Jin**, Xinping Yi, Pengfei Yang, Lijun Zhang, Sven Schewe, Xiaowei Huang
- [Enhancing Adversarial Training with Second-Order Statistics of Weights](https://arxiv.org/abs/2203.06020), CVPR 2022    
  **Gaojie Jin**, Xinping Yi, Wei Huang, Sven Schewe, Xiaowei Huang
- [How does Weight Correlation Affect the Generalisation Ability of Deep Neural Networks](https://arxiv.org/abs/2010.05983), NeurIPS 2020    
  **Gaojie Jin**, Xinping Yi, Liang Zhang, Lijun Zhang, Sven Schewe, Xiaowei Huang

# Teaching Assistant (University of Liverpool)

- Foundations of Computer Science
- Advanced Artificial Intelligence
- Object-oriented Programming
- Software Engineering I
- Computer Vision

# Reviewer
- ICML 2021, 2022
- NeurIPS 2021, 2022
- ICLR 2022, 2023
- AAAI 2023
