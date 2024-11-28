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
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D student at degree College of Computer Science and Technology, <a href="https://english.nudt.edu.cn/">National University of Defence Technology (NUDT)</a>. My supervised by Prof. <a href="https://xinwangliu.github.io/">Xinwang Liu</a> and Prof. En Zhu in Pattern Recognition Machine Intelligence Lab (PRMI). 

My research interests include graph neural networks, recommender system, multi-view learning and LLM. I have published serveral papers at the top international AI conferences and journals, such AAAI, ICDE, NeurIPS, TNNLS...



# 🔥 News
- *2024.11*: &nbsp;🎉🎉 One paper has been accepted by ICDE 2025. 
- *2024.11*: &nbsp;🎉🎉 I won the China National Scholarship for Phd Students.
- *2024.09*: &nbsp;🎉🎉 One paper has been accepted by NeurIPS 2024.
- *2024.07*: &nbsp;🎉🎉 I was awarded the China Scholarship Countil Scholarship.
- *2024.07*: &nbsp;🎉🎉 Three papers have been accepted by ACM MM 2024.
- *2024.05*: &nbsp;🎉🎉 One paper has been accepted by IEEE TNNLS 2024.
- *2024.02*: &nbsp;🎉🎉 One paper has been accepted by CVPR 2024.
- *2024.01*: &nbsp;🎉🎉 Two papers have been accepted by ACM TKDD 2024.
- *2024.01*: &nbsp;🎉🎉 One paper has been accepted by IEEE TNNLS 2024.
- *2023.12*: &nbsp;🎉🎉 Two papers have been accepted by AAAI 2024.
- *2023.12*: &nbsp;🎉🎉 One paper has been accepted by ICDE 2024.
- *2023.07*: &nbsp;🎉🎉 Five papers have been accepted by ACM MM 2023.
- *2023.07*: &nbsp;🎉🎉 One paper has been accepted by IEEE TNNLS 2023.
- *2023.06*: &nbsp;🎉🎉 One paper has been accepted by IEEE TKDE 2023.
- *2023.04*: &nbsp;🎉🎉 One paper has been accepted by ICML 2023.
- *2023.04*: &nbsp;🎉🎉 One paper has been accepted by IEEE TNNLS 2023.
- *2023.04*: &nbsp;🎉🎉 One paper has been accepted by IEEE TAI 2023.
- *2022.12*: &nbsp;🎉🎉 I won the China National Scholarship for Graduate Students.
- *2022.11*: &nbsp;🎉🎉 Two papers have been accepted by AAAI 2023.
- *2022.06*: &nbsp;🎉🎉 One paper has been accepted by IEEE TNNLS 2022.
- *2021.12*: &nbsp;🎉🎉 One paper has been accepted by AAAI 2022.
- *2020.12*: &nbsp;🎉🎉 I won the China National Scholarship for Undergraduate Students.

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDE 2025</div><img src='images/ICDE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DaRec: A Disentangled Alignment Framework for Large Language Model and Recommender System](https://arxiv.org/pdf/2408.08231) 

**Xihong Yang**, Heming Jing, Zixing Zhang, Jindong Wang, Huakang Niu, Shuaiqiang Wang, Yu Lu, Jufeng Wang, Dawei Yin, Xinwang Liu, En Zhu, Defu Lian, Erxue Min
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We prove that reducing the gap to zero between collaborative models and LLMs may not always benefit the performance when the gap between two models is large. We propose a novel plug-and-play alignment framework for LLMs and collaborative models.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/GraphLearner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GraphLearner: Graph Node Clustering with  Fully Learnable Augmentation](https://dl.acm.org/doi/abs/10.1145/3664647.3680602) 

[**Code**](https://github.com/xihongyang1999/GraphLearner) 

**Xihong Yang**, Erxue Min, Ke Liang, Yue Liu, Siwei Wang, Sihang Zhou, Huijun Wu, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In our method, we introduce learnable augmentors to generate high-quality and task-specific augmented samples for CDGC. GraphLearner incorporates two learnable augmentors specifically designed for capturing attribute and structural information. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM TKDD 2024</div><img src='images/MGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mixed Graph Contrastive Network for Semi-Supervised Node Classification](https://dl.acm.org/doi/abs/10.1145/3641549) 

[**Code**](https://github.com/xihongyang1999/MGCN) 

**Xihong Yang**, Yiqi Wang, Yue Liu, Yi Wen, Lingyuan Meng, Sihang Zhou, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In our method, we improve the discriminative capability of the latent embeddings by an interpolation based augmentation strategy and a correlation reduction mechanism.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/convert.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CONVERT: Contrastive Graph Clustering with Reliable Augmentation](https://arxiv.org/pdf/2308.08963.pdf) 

[**Code**](https://github.com/xihongyang1999/CONVERT) 

**Xihong Yang**, Cheng Tan, Yue Liu, Ke Liang, Sihang Zhou, Siwei Wang, Jun Xia, Stan Z.Li, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel CONtrastiVe Graph ClustEring network with Reliable AugmenTation (COVERT).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/dealmvc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DealMVC: Dual Contrastive Calibration for Multi-view Clustering](https://arxiv.org/pdf/2308.09000)

[**Code**](https://github.com/xihongyang1999/DealMVC) 

**Xihong Yang**, Jiaqi Jin, Siwei Wang, Ke Liang, Yue Liu, Yi Wen, Suyuan Liu, Sihang Zhou, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel Dual contrastive calibration network for Multi-View Clustering (DealMVC).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/yang_CCGC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cluster-guided Contrastive Graph Clustering Network](https://ojs.aaai.org/index.php/AAAI/article/download/26285/26057) 

[**Code**](https://github.com/xihongyang1999/CCGC) 

**Xihong Yang**, Yue Liu, Sihang Zhou, Siwei Wang, Wenxuan Tu, Qun Zheng, Xinwang Liu, Liming Fang, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Contrastive deep Graph Clustering network (CCGC) is proposed by mining the intrinsic supervision information in the high-confidence clustering results.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS 2022</div><img src='images/ICL_SSL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interpolation-based Contrastive Learning for Few-Label Semi-Supervised Learning](https://ieeexplore.ieee.org/abstract/document/9817089/) 

[**Code**](https://github.com/xihongyang1999/ICL_SSL) 

**Xihong Yang**, Xiaochang Hu, Sihang Zhou, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this paper, we propose an interpolation-based method to construct more reliable positive sample pairs;
- we design a novel contrastive loss to guide the embedding of the learned network to change linearly between samples so as to improve the discriminative capability of the network by enlarging the margin decision boundaries.
</div>
</div>



- Darec: A disentangled alignment framework for large language model and recommender system, **Xihong Yang**, Heming Jing, Zixing Zhang, Jindong Wang, Huakang Niu, Shuaiqiang Wang, Yu Lu, Jufeng Wang, Dawei Yin, Xinwang Liu, En Zhu, Defu Lian, Erxue Min, ICDE 2025, **CCF-A**.
- Evaluate then Cooperate: Shapley-based View Cooperation Enhancement for Multi-view Clustering, Fangdi Wang, Jiaqi Jin, Jingtao Hu, Suyuan Liu, **Xihong Yang**, Siwei Wang, Xinwang Liu, En Zhu, NeurIPS 2024, **CCF-A**.
- GraphLearner: Graph Node Clustering with  Fully Learnable Augmentation, **Xihong Yang**, Erxue Min, Ke Liang, Yue Liu, Siwei Wang, Sihang Zhou, Huijun Wu, Xinwang Liu, En Zhu, ACM MM 2024, **CCF-A**.
- View Gap Matters: Cross-view Topology and Information Decoupling for Multi-view Clustering, Fangdi Wang, Jiaqi Jin, Zhibin Dong, **Xihong Yang**, Yu Feng, Xinzhong Zhu, Siwei Wang, Tianrui Liu, Xinwang Liu, En Zhu, ACM MM 2024, **CCF-A**.
- Test-Time Training on Graphs with Large Language Models (LLMs), Jiaxin Zhang, Yiqi Wang, **Xihong Yang**, Siwei Wang, Yu Feng, Yu Shi, Ruichao Ren, Xinwang Liu, En Zhu, ACM MM 2024, **CCF-A**.
- Improved Dual Correlation Reduction Network With Affinity Recovery, Yue Liu, Sihang Zhou, **Xihong Yang**, Xinwang Liu, Wenxuan Tu, Liang Li, Xin Xu, Fuchun Sun, IEEE TNNLS 2024, **CCF-B**.
- Learn from View Correlation: An Anchor Enhancement Strategy for Multi-view Clustering, Suyuan Liu, Ke Liang, Zhibin Dong, Siwei Wang, **Xihong Yang**, Sihang Zhou, En Zhu, Xinwang Liu, CVPR 2024, **CCF-A**.
- Mixed Graph Contrastive Network for Semi-Supervised Node Classification, **Xihong Yang**, Yiqi Wang, Yue Liu, Yi Wen, Lingyuan Meng, Sihang Zhou, Xinwang Liu, En Zhu, ACM TKDD 2024, **CCF-B**.
- A Fully Test-Time Training Framework for Semi-Supervised Node Classification on Out-of-Distribution Graphs, Jiaxin Zhang, Yiqi Wang, **Xihong Yang**, En Zhu, ACM TKDD 2024, **CCF-B**.
- SARF: Aliasing Relation–Assisted Self-Supervised Learning for Few-Shot Relation Reasoning, Lingyuan Meng, Ke Liang, Bin Xiao, Sihang Zhou, Yue Liu, Meng Liu, **Xihong Yang**, Xinwang Liu, Jinyan Li, IEEE TNNLS 2024, **CCF-B**.
- Sample-Level Cross-View Similarity Learning for Incomplete Multi-View Clustering, Suyuan Liu, Junpu Zhang, Yi Wen, **Xihong Yang**, Siwei Wang, Yi Zhang, En Zhu, Chang Tang, Long Zhao, Xinwang Liu, AAAI 2024, **CCF-A**.
- Cross-gate mlp with protein complex invariant embedding is a one-shot antibody designer, Cheng Tan, Zhangyang Gao, Lirong Wu, Jun Xia, Jiangbin Zheng, **Xihong Yang**, Yue Liu, Bozhen Hu, Stan Z Li, AAAI 2024, **CCF-A**.
- DiscoGNN: A Sample-Efficient Framework for Self-Supervised Graph Representation Learning, Jun Xia, Shaorong Chen, Yue Liu, Zhangyang Gao, Jiangbin Zheng, **Xihong Yang**, Stan Z Li, ICDE 2024, **CCF-A**.
- Topological structure learning for weakly-supervised out-of-distribution detection, Rundong He, Rongxue Li, Zhongyi Han, **Xihong Yang**, Yilong Yin, ACM MM 2023, **CCF-A**.
- Efficient Multi-View Graph Clustering with Local and Global Structure Preservation, Yi Wen, Suyuan Liu, Xinhang Wan, Siwei Wang, Ke Liang, Xinwang Liu, **Xihong Yang**, Pei Zhang, ACM MM 2023, **CCF-A**.
- CONVERT: Contrastive Graph Clustering with Reliable Augmentation, **Xihong Yang**, Cheng Tan, Yue Liu, Ke Liang, Siwei Wang, Sihang Zhou, Jun Xia, Stan Z Li, Xinwang Liu, En Zhu, ACM MM 2023, **CCF-A**.
- DealMVC: Dual Contrastive Calibration for Multi-view Clustering, **Xihong Yang**, Jiaqi Jin, Siwei Wang, Ke Liang, Yue Liu, Yi Wen, Suyuan Liu, Sihang Zhou, Xinwang Liu, En Zhu, ACM MM 2023, **CCF-A**.
- Reinforcement Graph Clustering with Unknown Cluster Number, Yue Liu, Ke Liang, Jun Xia, **Xihong Yang**, Sihang Zhou, Meng Liu, Xinwang Liu, Stan Z Li, ACM MM 2023, **CCF-A**.
- Task-related saliency for few-shot image classification, Zhenyu Zhou, Lei Luo, Sihang Zhou, Wang Li, **Xihong Yang**, Xinwang Liu, En Zhu, IEEE TNNLS 2023, **CCF-B**.
- Simple contrastive graph clustering, Yue Liu, **Xihong Yang**, Sihang Zhou, Xinwang Liu, IEEE TNNLS 2023, **CCF-B**
- Knowledge Graph Contrastive Learning based on Relation-Symmetrical Structure, Ke Liang, Yue Liu, Sihang Zhou, Xinwang Liu, Wenxuan Tu, **Xihong Yang**, IEEE TKDE 2023, **CCF-A**.
- Dink-Net: Neural Clustering on Large Graphs, Yue Liu, Ke Liang, Jun Xia, Sihang Zhou, **Xihong Yang**, Xinwang Liu, Stan Z Li, ICML 2023, **CCF-A**.
- Patch-Mixing Contrastive Regularization for Few-Label Semi-Supervised Learning, Xiaochang Hu, Xin Xu, Yujun Zeng, **Xihong Yang**, IEEE TAI 2023.
- Cluster-Guided Contrastive Graph Clustering Network, **Xihong Yang**, Yue Liu, Sihang Zhou, Siwei Wang, Wenxuan Tu, Qun Zheng, Xinwang Liu, Liming Fang, En Zhu, AAAI 2023, **CCF-A**.
- Hard Sample Aware Network for Contrastive Deep Graph Clustering, Yue Liu, **Xihong Yang**, Sihang Zhou, Xinwang Liu, Zhen Wang, Ke Liang, Wenxuan Tu, Liang Li, Jingcan Duan, Cancan Chen, AAAI 2023, **CCF-A**.
- Interpolation-based Contrastive Learning for Few-Label Semi-Supervised Learning, **Xihong Yang**, Xiaochang Hu, Sihang Zhou, Xinwang Liu, En Zhu, IEEE TNNLS 2022, **CCF-B**.
- Deep graph clustering via dual correlation reduction, Yue Liu, Wenxuan Tu, Sihang Zhou, Xinwang Liu, Linxuan Song, **Xihong Yang**, En Zhu, AAAI 2022, **CCF-A**.


# 💻 Internships
- *2024.03 - 2024.11*, [Baidu](https://home.baidu.com/), China.
- *2020.09 - 2020.11*, [PICO](https://www.picoxr.com/cn), China.

# 🎖 Honors and Awards
- *2024.11* I won the China National Scholarship for Phd Students.
- *2024.07* I was awarded the China Scholarship Countil Scholarship.
- *2022.11* I won the China National Scholarship for Graduate Students.
- *2020.11* I won the China National Scholarship for Undergraduate Students.

# 💻 Services
- PC for Conference:
  ICML'23/24, ICLR'24/25, NeurIPS'23/24
  CVPR'24/25, AAAI'23/24/25,ACM MM'23/24,
  WWW'24, KDD'23/24, CIKM'24
  
- PC for Journal:
  IEEE TNNLS/TCSVT/TKDE/TCSS
  ACM TKDD/TOMM


# 📖 Educations
- *2024.11 - now*, Visiting PhD Student, <a href="https://www.nus.edu.sg/">National University of Singapore</a>, supervised by Prof. <a href="https://yuemingjin.github.io/">Yueming Jin</a>
- *2023.03 - now*, PhD Student, <a href="https://english.nudt.edu.cn/">National University of Defence Technology</a>, supervised by Prof. <a href="https://xinwangliu.github.io/">Xinwang Liu</a>
- *2023.07 - 2024.03*, Visiting Student @ <a href="https://www.ustc.edu.cn/">University of Science and Technology of China</a> supervised by Prof. <a href="https://scholar.google.com/citations?user=QW0ad4sAAAAJ&hl=zh-CN&oi=ao">Defu Lian</a>.
- *2022.12 - 2024.02*, Visiting Student @ <a href="https://en.westlake.edu.cn/">Westlake University</a>, working with <a href="https://scholar.google.com/citations?user=6kTV6aMAAAAJ&hl=zh-CN">Cheng Tan</a>, supervised by Prof. <a href="https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN&oi=ao">Stan Z. Li</a>.
- *2021.09 - 2023.02*, Master Student, <a href="https://english.nudt.edu.cn/">National University of Defence Technology</a>, supervised by Prof. <a href="https://xinwangliu.github.io/">Xinwang Liu</a>


# 💬 Invited Talks
- *2023.10*, ACM MM Oral Presentation.
- *2022.11*, AAAI Oral Presentation.

