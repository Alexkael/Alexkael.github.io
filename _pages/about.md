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

I am an Assistant Professor in AI & CS at the University of Macau, previously I worked as an Assistant Professor at the University of Exeter, UK, and as a Research Associate Professor at the Chinese Academy of Sciences. 

I am interested in developing **reliable** (e.g., robust, generalisable, and efficient [[NeurIPS20](https://proceedings.neurips.cc/paper_files/paper/2020/file/f48c04ffab49ff0e5d1176244fdfb65c-Paper.pdf),[CVPR22](https://arxiv.org/abs/2203.06020),[23](https://openaccess.thecvf.com/content/CVPR2023/html/Jin_Randomized_Adversarial_Training_via_Taylor_Expansion_CVPR_2023_paper.html),[ICCV23a](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_SAFARI_Versatile_and_Efficient_Evaluations_for_Robustness_of_Interpretability_ICCV_2023_paper.html),[TIFS25](https://ieeexplore.ieee.org/abstract/document/10969094),[ICLR25a](https://arxiv.org/abs/2501.06842)]) algorithms for modern machine learning models and applications [[ICCV23b](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_SAFARI_Versatile_and_Efficient_Evaluations_for_Robustness_of_Interpretability_ICCV_2023_paper.html),[AAAI23](https://ojs.aaai.org/index.php/AAAI/article/view/26756),[ECCV24](https://link.springer.com/chapter/10.1007/978-3-031-72848-8_16)]. I focuse on aligning AI with human rules/preferences [[ICML24](https://proceedings.mlr.press/v235/dong24c.html),[ICLR25b](https://arxiv.org/abs/2501.13273)], with an emphasis on providing theoretical guarantees and statistical analyses [[TMLR22](https://arxiv.org/abs/2201.09209),[TPAMI25](https://ieeexplore.ieee.org/document/11027475)].

Currently, my research interests include, but are not limited to:

- Trustworthy Human–GenAI Alignment: Developing unified statistical frameworks, e.g., combining PAC-Bayesian theory, conformal prediction, and adversarial analysis, to provide rigorous guarantees for human–GenAI alignment. [[ICML26a](https://arxiv.org/pdf/2605.15416),[EMNLP26](https://arxiv.org/abs/2608.25824)]

- Efficiency Robustness of GenAI: Building empirical and theoretical foundations to analyse and mitigate vulnerabilities in reasoning efficiency. [[ICML26b](https://arxiv.org/pdf/2605.08876),[AAAI26](https://ojs.aaai.org/index.php/AAAI/article/view/40486)]

I am pleased to announce multiple openings for PhD and post-doctoral positions for the 2026/27 academic year. If you are interested in these opportunities or would like to discuss potential collaborations, please don't hesitate to contact me at gaojiejin at um dot edu dot mo.

# Recent News
- (08/2026) I will be serving as an Area Chair for ICLR 2027.
- (08/2026) One paper accepted to EMNLP 2026 (Findings), one paper accepted to MICCAI 2026.
- (05/2026) Served as a PhD Viva external examiner for a candidate at King's College London.
- (04/2026) Three papers accepted to ICML 2026, congrats to all coauthors, congrats to Xinyu for his first paper.
- (03/2026) I will be serving as an Area Chair for NeurIPS 2026.
- (02/2026) One paper accepted to CVPR 2026 (**Oral**), one paper accepted to IEEE ISIT 2026.
- (01/2026) One paper accepted to ICLR 2026, one paper accepted to IEEE TIP, one paper accepted to ICASSP 2026.     
- (11/2025) I will be serving as an Associate Editor for Theoretical Computer Science.  
- (11/2025) Two papers accepted to AAAI 2026.  
- (10/2025) Got a grant from Isambard-AI with 10000 GPU hours. 
- (09/2025) Got a grant from NVIDIA Academic Grant Program.
- (09/2025) I will be serving as an Area Chair for ICLR 2026.
- (06/2025) One paper accepted to TMLR.
- (06/2025) One paper accepted to IEEE TPAMI.
- (05/2025) I will be serving as an Area Chair for NeurIPS 2025 (Position Paper Track).
- (04/2025) One paper accepted to IEEE TIFS.
- (02/2025) Got two PhD studentships from the EU Horizon project.
- (01/2025) Two papers accepted to ICLR 2025.
- (07/2024) Start my position as a Lecturer (Assistant Professor) at Exeter.
- (06/2024) One paper accepted to ECCV 2024.
- (01/2024) One paper accepted to ICML 2024.

# Funding & Grants
- Exploiting Robustness of Reasoning Efficiency in Agentic AI (PI) (2025-2026)  
  Funded by AIRR Isambard-AI (10000 GPU hours)
- Exploiting Overthinking Attacks on GenAI (PI) (2025-2026)  
  Funded by NVIDIA Academic Grant Program (NVIDIA DGX Spark)
- Robustifying Generative AI through Human-Centric Integration of Neural and Symbolic Methods (External Participant) 2025 - 2028  
  Funded by EU Horizon.  
- FOCETA (Foundations for Continuous Engineering of Trustworthy Autonomy) (Research Assistant) 2021 - 2023  
  Funded by EU H2020. 
- EnnCore (End-to-End Conceptual Guarding of Neural Architectures) (Research Assistant) 2020 - 2024  
  Funded by EPSRC. 
- SOLITUDE (Safety Argument for Learning-enabled Autonomous Underwater Vehicles) (Research Assistant) 2020 - 2022  
  Funded by UK DSTL. 
  
# Publications
#:Equal Contribution, ✉️:Corresponding Author
## 2026

1. **GradientStabilizer: Fix the Norm, Not the Gradient**  
   Tianjin Huang, Zhangyang Wang, Haotian Hu, Zhenyu Zhang, **Gaojie Jin**, et al.  
   *International Conference on Machine Learning (ICML), 2026.*

2. **Margin-Adaptive Confidence Ranking for Reliable LLM Judgement**  
    **G. Jin**, Y. Tao, L. Yu, T. Huang.  
    *International Conference on Machine Learning (ICML), 2026.*

3. **OTora: A Unified Red Teaming Framework for Reasoning-Level Denial-of-Service in LLM Agents**  
   X. Li, R. Mu, L. Li, T. Huang, **G. Jin✉️**.  
   *International Conference on Machine Learning (ICML), 2026.*

4. **Preference Alignment on Diffusion Models: A Comprehensive Survey for Image Generation and Editing**  
   S. Wu, X. Si, C. Xing, J. Wang, **G. Jin**, G. Cheng, X. Huang.  
   *Computer Science Review, 61, 100900, 2026.*

5. **BadThink: Triggered Overthinking Attacks on Chain-of-Thought Reasoning in Large Language Models**  
   S. Liu, R. Li, L. Yu, L. Zhang, Z. Liu, **G. Jin✉️**.  
   *AAAI Conference on Artificial Intelligence (AAAI), 2026.*

6. **CluCERT: Certifying LLM Robustness via Clustering-Guided Denoising Smoothing**  
   Z. Wang, **G. Jin**, J. Hu, R. Mu.  
   *AAAI Conference on Artificial Intelligence (AAAI), 2026.*

7. **Confusion-Aware Spectral Regularizer for Long-Tailed Recognition**  
   Z. Zhu#, **G. Jin#**, H. Zhu#, S. Y. Lu#, Y. Zhang, Z. Fu, R. Mu, G. Zhang, Z. Sun, et al.  
   *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026. Oral.*

8. **Dual-Kernel Adapter: Expanding Spatial Horizons for Data-Constrained Medical Image Analysis**  
   Z. Zhu, H. Zhu, S. Lu, X. Li, Y. Meng, **G. Jin**, L. Yin, L. Hu, D. Wang, L. Liu, et al.  
   *International Conference on Learning Representations (ICLR), 2026.*

9. **StealthMark: Harmless and Stealthy Ownership Verification for Medical Segmentation via Uncertainty-Guided Backdoors**  
   Q. Yu, C. Zhang, **G. Jin**, T. Huang, W. Zhou, W. Li, X. Jin, B. Huang, Y. Zhao, et al.  
   *IEEE Transactions on Image Processing (TIP), 2026.*

10. **Localize-Then-Decide Guarantees for LLM Judgments**  
   X. Li, Y. Zhou, G. Cao, Z. Fu, T. Huang, **G. Jin✉️**.  
   *Findings of the Association for Computational Linguistics: EMNLP, 2026.*

11. **CPR: Chained Perceptual Refinement for Coarse-to-Fine Medical Image Classification**  
    S. Y. Lu, H. Zhu, Z. Zhu, **G. Jin**, Z. Fu, L. Yin, K. Li, L. Liu, T. Huang.  
    *International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2026.*

12. **A Unified Framework for PAC-Bayesian Norm-based Generalization Bounds**  
    X. Yi, **G. Jin**, X. Huang, S. Jin.  
    *IEEE International Symposium on Information Theory (ISIT), 2026, pp. 1–6.*

13. **TRAJRS: Towards Certified Robustness in Pedestrian Trajectory Prediction**  
    L. Zhang, **G. Jin**, Y. Shi, Q. Li, C. C. Huang, D. N. Jansen, L. Zhang.  
    *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2026.*


## 2025

1. **Safeguarding Large Language Models: A Survey**  
   Y. Dong, R. Mu, Y. Zhang, S. Sun, T. Zhang, C. Wu, **G. Jin**, Y. Qi, J. Hu, J. Meng, et al.  
   *Artificial Intelligence Review, 58(12), 382, 2025.*

2. **SPAM: Spike-Aware Adam with Momentum Reset for Stable LLM Training**  
   T. Huang, Z. Zhu, **G. Jin**, L. Liu, Z. Wang, S. Liu.  
   *International Conference on Learning Representations (ICLR), 2025.*

3. **Enhancing Robust Fairness via Confusional Spectral Regularization**  
   **G. Jin**, S. Wu, J. Liu, T. Huang, R. Mu.  
   *International Conference on Learning Representations (ICLR), 2025.*

4. **Invariant Correlation of Representation with Label: Enhancing Domain Generalization in Noisy Environments**  
   **G. Jin**, R. Mu, X. Yi, X. Huang, L. Zhang.  
   *IEEE Transactions on Information Forensics and Security (TIFS), 2025.*

5. **Toward Linearly Regularizing the Geometric Bottleneck of Linear Generalized Attention**  
   J. Liu, X. Yi, X. Yin, Y. Song, **G. Jin**, X. Huang.  
   *Transactions on Machine Learning Research (TMLR), 2025.*

6. **S²O: Enhancing Adversarial Training with Second-Order Statistics of Weights**  
   **G. Jin**, X. Yi, W. Huang, S. Schewe, X. Huang.  
   *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2025.*  


## 2024

1. **Position: Building Guardrails for Large Language Models Requires Systematic Design**  
   D. Yi, R. Mu, **G. Jin**, Y. Qi, J. Hu, X. Zhao, J. Meng, W. Ruan, X. Huang.  
   *International Conference on Machine Learning (ICML), 2024.*

2. **Formal Verification of Robustness and Resilience of Learning-Enabled State Estimation Systems**  
   W. Huang, Y. Zhou, **G. Jin**, Y. Sun, J. Meng, F. Zhang, X. Huang.  
   *Neurocomputing, 585, 127643, 2024.*

3. **Class-Aware Cross Pseudo Supervision Framework for Semi-Supervised Multi-organ Segmentation in Abdominal CT Scans**  
   D. Yang, H. Zhao, **G. Jin**, H. Meng, L. Zhang.  
   *Chinese Conference on Pattern Recognition and Computer Vision (PRCV), 2024.*

4. **Out-of-Bounding-Box Triggers: A Stealthy Approach to Cheat Object Detectors**  
   T. Lin, L. Yu, **G. Jin**, R. Li, P. Wu, L. Zhang.  
   *European Conference on Computer Vision (ECCV), 2024.*


## 2023

1. **A Survey of Safety and Trustworthiness of Large Language Models through the Lens of Verification and Validation**  
   X. Huang, W. Ruan, W. Huang, **G. Jin**, Y. Dong, C. Wu, S. Bensalem, R. Mu, et al.  
   *Artificial Intelligence Review, 2023.*

2. **Randomized Adversarial Training via Taylor Expansion**  
   **G. Jin**, X. Yi, D. Wu, R. Mu, X. Huang.  
   *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023.*

3. **SAFARI: Versatile and Efficient Evaluations for Robustness of Interpretability**  
   W. Huang, X. Zhao, **G. Jin**, X. Huang.  
   *IEEE/CVF International Conference on Computer Vision (ICCV), 2023.*

4. **Optimising Event-Driven Spiking Neural Network with Regularisation and Cutoff**  
   D. Wu, **G. Jin**, H. Yu, X. Yi, X. Huang.  
   *Frontiers in Neuroscience, 2023.*

5. **Certified Policy Smoothing for Cooperative Multi-Agent Reinforcement Learning**  
   R. Mu, W. Ruan, L. S. Marcolino, **G. Jin**, Q. Ni.  
   *AAAI Conference on Artificial Intelligence (AAAI), 2023.*

6. **TrajPAC: Towards Robustness Verification of Pedestrian Trajectory Prediction Models**  
   L. Zhang, N. Xu, P. Yang, **G. Jin✉️**, C. C. Huang, L. Zhang.  
   *IEEE/CVF International Conference on Computer Vision (ICCV), 2023.*

7. **Machine Learning Safety**  
   X. Huang, **G. Jin**, W. Ruan.  
   *Machine Learning Safety, pp. 3–13, 2023.*


## 2022

1. **S²O: Enhancing Adversarial Training with Second-Order Statistics of Weights**  
   **G. Jin**, X. Yi, W. Huang, S. Schewe, X. Huang.  
   *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022.*  
   *(Later extended in IEEE TPAMI, 2025.)*

2. **Weight Expansion: A New Perspective on Dropout and Generalization**  
   **G. Jin**, X. Yi, P. Yang, L. Zhang, S. Schewe, X. Huang.  
   *Transactions on Machine Learning Research (TMLR), 2022.*


## 2020

1. **How Does Weight Correlation Affect the Generalisation Ability of Deep Neural Networks**  
   **G. Jin**, X. Yi, L. Zhang, L. Zhang, S. Schewe, X. Huang.  
   *Advances in Neural Information Processing Systems (NeurIPS), 2020.*

[Full list](https://scholar.google.com/citations?user=n_cu7jwAAAAJ&hl=en)


# Teaching 
- ECM1416: Computational Mathematics
- COMM113: Deep Learning


# Supervised Students (as Primary Supervisor)
- Xinyu Li (PhD candidate at Exeter since 02/2026)  
  Published: ICML 2026, EMNLP 2026 (Findings)  
- Qiutong Xu (PhD candidate at Exeter, expected since 11/2026)
- Jingxiao Li (PhD candidate at Macau since 09/2026)
- Zekang Wang (PhD candidate at Macau since 09/2026)
- Hongyi Zhang (Master Student at Macau since 09/2026)
- Yuchen Liu (Master Student at Macau since 09/2026)
- Siyuan Lu (Master Student at Macau since 09/2026)  


# Academic Service
- Reviewer  
  ICML, NeurIPS, ICLR, AISTATS, AAAI, CVPR, ICCV, ECCV, JMLR, IJCV, TMLR, TIFS, TDSC
- Area Chair  
  NeurIPS 2025/2026, ICLR 2026/2027
- Associate Editor  
  Theoretical Computer Science
- Organise the workshop [TrustRL: Trustworthy in Reinforcement Learning](https://www.ieee-smart-world.org/2024/atc/workshops.php) at ATC 2024
