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

I am a Ph.D student at degree College of Computer Science and Technology, <a href="https://english.nudt.edu.cn/">National University of Defence Technology (NUDT)</a>. He is supervised by Prof. <a href="https://xinwangliu.github.io/">Xinwang Liu</a> and Prof. En Zhu in Pattern Recognition \& Machine Intelligence Lab (PRMI). 

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

[GraphLearner: Graph Node Clustering with  Fully Learnable Augmentation](https://dl.acm.org/doi/abs/10.1145/3664647.3680602) | [**Code**](https://github.com/xihongyang1999/GraphLearner) 
**Xihong Yang**, Erxue Min, Ke Liang, Yue Liu, Siwei Wang, Sihang Zhou, Huijun Wu, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In our method, we introduce learnable augmentors to generate high-quality and task-specific augmented samples for CDGC. GraphLearner incorporates two learnable augmentors specifically designed for capturing attribute and structural information. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM TKDD 2024</div><img src='images/MGCN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mixed Graph Contrastive Network for Semi-Supervised Node Classification](https://dl.acm.org/doi/abs/10.1145/3641549) | [**Code**](https://github.com/xihongyang1999/MGCN) 

**Xihong Yang**, Yiqi Wang, Yue Liu, Yi Wen, Lingyuan Meng, Sihang Zhou, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In our method, we improve the discriminative capability of the latent embeddings by an interpolation based augmentation strategy and a correlation reduction mechanism.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/convert.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CONVERT: Contrastive Graph Clustering with Reliable Augmentation](https://arxiv.org/pdf/2308.08963.pdf) | [**Code**](https://github.com/xihongyang1999/CONVERT) 

**Xihong Yang**, Cheng Tan, Yue Liu, Ke Liang, Sihang Zhou, Siwei Wang, Jun Xia, Stan Z.Li, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel CONtrastiVe Graph ClustEring network with Reliable AugmenTation (COVERT).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/dealmvc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DealMVC: Dual Contrastive Calibration for Multi-view Clustering](https://arxiv.org/pdf/2308.09000) | [**Code**](https://github.com/xihongyang1999/DealMVC) 

**Xihong Yang**, Jiaqi Jin, Siwei Wang, Ke Liang, Yue Liu, Yi Wen, Suyuan Liu, Sihang Zhou, Xinwang Liu, En Zhu
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel Dual contrastive calibration network for Multi-View Clustering (DealMVC).
</div>
</div>



- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
