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

I am a Lecturer (Assistant Professor) in Computer Science at the University of Exeter, previously I worked at the Chinese Academy of Sciences and the University of Liverpool. I earned my PhD from the University of Liverpool, under the supervision of [Prof. Xiaowei Huang](https://cgi.csc.liv.ac.uk/~xiaowei/) and [Prof. Xinping Yi](https://sites.google.com/site/xinpingyi00/).

I am interested in developing **reliable** (e.g., robust, generalisable, and efficient [[NeurIPS20](https://proceedings.neurips.cc/paper_files/paper/2020/file/f48c04ffab49ff0e5d1176244fdfb65c-Paper.pdf),[CVPR22](https://arxiv.org/abs/2203.06020),[23](https://openaccess.thecvf.com/content/CVPR2023/html/Jin_Randomized_Adversarial_Training_via_Taylor_Expansion_CVPR_2023_paper.html),[ICCV23a](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_SAFARI_Versatile_and_Efficient_Evaluations_for_Robustness_of_Interpretability_ICCV_2023_paper.html),[TIFS25](https://ieeexplore.ieee.org/abstract/document/10969094),[ICLR25a](https://arxiv.org/abs/2501.06842)]) algorithms for modern machine learning models and applications [[ICCV23b](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_SAFARI_Versatile_and_Efficient_Evaluations_for_Robustness_of_Interpretability_ICCV_2023_paper.html),[AAAI23](https://ojs.aaai.org/index.php/AAAI/article/view/26756),[ECCV24](https://link.springer.com/chapter/10.1007/978-3-031-72848-8_16)]. I focuse on **aligning AI with human rules/preferences** [[ICML24](https://proceedings.mlr.press/v235/dong24c.html),[ICLR25b](https://arxiv.org/abs/2501.13273)], with an emphasis on providing formal theoretical guarantees and rigorous **statistical** analyses [[TMLR22](https://arxiv.org/abs/2201.09209),[TPAMI25](https://ieeexplore.ieee.org/document/11027475)].

I am pleased to announce multiple openings for PhD and internship positions for the 2024/25 academic year. Scholarships are available through the [University of Exeter](https://www.exeter.ac.uk/study/pg-research/funding/phdfunding/) and the [CSC-Exeter program](https://www.exeter.ac.uk/study/pg-research/csc-scholarships/). If you are interested in these opportunities or would like to discuss potential collaborations, please don't hesitate to contact me at g.jin@exeter.ac.uk.

# Recent News
- (09/2025) Funded by Nvidia Academic Grant Program.
- (09/2025) I will be serving as an Area Chair for ICLR 2026.
- (06/2025) One paper accepted to TMLR.
- (06/2025) One paper accepted to IEEE TPAMI.
- (05/2025) I will be serving as an Area Chair for NeurIPS 2025 (Position Paper Track).
- (04/2025) One paper accepted to IEEE TIFS.
- (02/2025) Get two PhD studentships from the EU Horizon project.
- (01/2025) Two papers accepted to ICLR 2025.
- (07/2024) Start my position as a Lecturer (Assistant Professor) at Exeter.
- (06/2024) One paper accepted to ECCV 2024.
- (01/2024) One paper accepted to ICML 2024.

# Funding & Grants
- NVIDIA Academic Grant Program (2025): Exploiting Overthinking Attacks on GenAI (PI)
- Robustifying Generative AI through Human-Centric Integration of Neural and Symbolic Methods (External Participant) 2025 - 2028  
  Funded by EU Horizon.  
- FOCETA (Foundations for Continuous Engineering of Trustworthy Autonomy) (Research Assistant) 2021 - 2023  
  Funded by EU H2020. 
- EnnCore (End-to-End Conceptual Guarding of Neural Architectures) (Research Assistant) 2020 - 2024  
  Funded by EPSRC. 
- SOLITUDE (Safety Argument for Learning-enabled Autonomous Underwater Vehicles) (Research Assistant) 2020 - 2022  
  Funded by UK DSTL. 
  
# Selected Publications
<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/images/iclr2025.jpg" style="width: 200px; margin-right: 20px;" alt="Paper image">
  <div>
    <a href="https://arxiv.org/pdf/2501.13273" target="_blank"><b>Enhancing Robust Fairness via Confusional Spectral Regularization</b></a>, ICLR 2025<br>
    <b>Gaojie Jin</b>, Sihao Wu, Jiaxu Liu, Tianjin Huang, Ronghui Mu
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/images/TPAMI2025.jpg" style="width: 200px; margin-right: 20px;" alt="Paper image">
  <div>
    <a href="https://ieeexplore.ieee.org/document/11027475" target="_blank"><b>Enhancing Adversarial Training with Second-Order Statistics of Weights</b></a>, CVPR 2022, IEEE TPAMI 2025<br>
    <b>Gaojie Jin</b>, Xinping Yi, Wei Huang, Sven Schewe, Xiaowei Huang
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/images/TIFS2025.jpg" style="width: 200px; margin-right: 20px;" alt="Paper image">
  <div>
    <a href="https://ieeexplore.ieee.org/abstract/document/10969094" target="_blank"><b>Invariant Correlation of Representation with Label</b></a>, IEEE TIFS 2025<br>
    <b>Gaojie Jin</b>, Ronghui Mu, Xinping Yi, Xiaowei Huang, Lijun Zhang
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/images/CVPR2023_.jpg" style="width: 200px; margin-right: 20px;" alt="Paper image">
  <div>
    <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Jin_Randomized_Adversarial_Training_via_Taylor_Expansion_CVPR_2023_paper.pdf" target="_blank"><b>Randomized Adversarial Training via Taylor Expansion</b></a>, CVPR 2023<br>
    <b>Gaojie Jin</b>, Xinping Yi, Dengyu Wu, Ronghui Mu, Xiaowei Huang
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/images/NeurIPS2020_.jpg" style="width: 200px; margin-right: 20px;" alt="Paper image">
  <div>
    <a href="https://arxiv.org/abs/2010.05983" target="_blank"><b>How does Weight Correlation Affect the Generalisation Ability of Deep Neural Networks</b></a>, NeurIPS 2020<br>
    <b>Gaojie Jin</b>, Xinping Yi, Liang Zhang, Lijun Zhang, Sven Schewe, Xiaowei Huang
  </div>
</div>

[Full list](https://scholar.google.com/citations?user=n_cu7jwAAAAJ&hl=en)


# Teaching 
- ECM1416: Computational Mathematics

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/images/MLsafety.jpg" style="width: 100px; margin-right: 20px;" alt="Paper image">
  <div>
    <a href="https://link.springer.com/book/10.1007/978-981-19-6814-3" target="_blank"><b>Textbook: Machine Learning Safety</b></a>, Springer<br>
    Xiaowei Huang, <b>Gaojie Jin</b>, Wenjie Ruan
  </div>
</div>

# Academic Service
- Reviewer  
  ICML, NeurIPS, ICLR, AISTATS, AAAI, CVPR, ICCV, ECCV, JMLR, IJCV, TMLR, TIFS, TDSC
- Area Chair  
  NeurIPS 2025 (Position Paper Track), ICLR 2026
- Organise the workshop [TrustRL: Trustworthy in Reinforcement Learning](https://www.ieee-smart-world.org/2024/atc/workshops.php) at ATC 2024
