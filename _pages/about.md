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

I am a lecturer in Computer Science at the University of Exeter.
Prior to that I worked at the Chinese Academy of Sciences, University of Liverpool. I obtained my PhD in the Department of Computer Science at the University of Liverpool, under the advisory of [Prof. Xiaowei Huang](https://cgi.csc.liv.ac.uk/~xiaowei/) and [Prof. Xinping Yi](https://sites.google.com/site/xinpingyi00/).

My research focuses on developing efficient, reliable algorithms (generalisation, robustness, privacy, interpretability, etc) for modern machine learning models and applications, with formal theoretical guarantees and analyses. I am also interested in building trustworthy LLMs.

# Publications 
- Out-of-Bounding-Box Trigger: A Stealthy Approach to Cheat Object Detector, ECCV 2024  
  Tao Lin, Lijia Yu, **Gaojie Jin**, Renjue Li, Peng Wu, Lijun Zhang
- Position: Building Guardrails for Large Language Models Requires Systematic Design, ICML 2024  
  D Yi, R Mu, **G Jin**, Y Qi, J Hu, X Zhao, J Meng, W Ruan, X Huang
- TrajPAC: Towards Robustness Verification of Pedestrian Trajectory Prediction Models, ICCV 2023  
  L Zhang, N Xu, P Yang, **G Jin**, CC Huang, L Zhang
- SAFARI: Versatile and Efficient Evaluations for Robustness of Interpretability, ICCV 2023  
  Wei Huang, Xingyu Zhao, **Gaojie Jin**, Xiaowei Huang
- [Randomized Adversarial Training via Taylor Expansion](https://openaccess.thecvf.com/content/CVPR2023/papers/Jin_Randomized_Adversarial_Training_via_Taylor_Expansion_CVPR_2023_paper.pdf), CVPR 2023  
  **Gaojie Jin**, Xinping Yi, Dengyu Wu, Ronghui Mu, Xiaowei Huang
- Certified Policy Smoothing for Cooperative Multi-Agent Reinforcement Learning, AAAI 2023  
  Ronghui Mu, Wenjie Ruan, LS Marcolino, **Gaojie Jin**, Qiang Ni
- [Weight Expansion: A New Perspective on Dropout and Generalization](https://openreview.net/forum?id=w3z3sN1b04), TMLR  
  **Gaojie Jin**, Xinping Yi, Pengfei Yang, Lijun Zhang, Sven Schewe, Xiaowei Huang
- [Enhancing Adversarial Training with Second-Order Statistics of Weights](https://arxiv.org/abs/2203.06020), CVPR 2022    
  **Gaojie Jin**, Xinping Yi, Wei Huang, Sven Schewe, Xiaowei Huang
- [How does Weight Correlation Affect the Generalisation Ability of Deep Neural Networks](https://arxiv.org/abs/2010.05983), NeurIPS 2020    
  **Gaojie Jin**, Xinping Yi, Liang Zhang, Lijun Zhang, Sven Schewe, Xiaowei Huang

# Teaching

- ECM1416: Computational Mathematics

# Reviewer
- ICML, NeurIPS, ICLR, AAAI, CVPR, ICCV, ECCV, JMLR, IJCV 
