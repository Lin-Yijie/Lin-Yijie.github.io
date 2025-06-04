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

<!-- Hi! My name is Yijie Lin.  -->
I am a Ph.D. student in the College of Computer Science at Sichuan University, advised by Prof.[Xi Peng](http://pengxi.me). 

My research mainly focuses on **Multi-modal Learning**, with contributions in:
- i) Robust Multi-modal Learning: I have worked extensively on tackling challenges such as modality missing (CVPR’21, TPAMI’22, AAAI’24-25) and noisy correspondence (ICCV’23, ICLR’24, NeurIPS’24) in image/video-text and image-image data. For a comprehensive overview of our work and insights on noisy correspondence, you can explore our repository [Noisy Correspondence Summary](https://github.com/XLearning-SCU/Awesome-Noisy-Correspondence).
- ii) Interactive Multi-modal Learning: I believe the future of multi-modal learning to center around interactions—between users (ICML'25, LLaVA-ReID), tools (ICML'25, Visual Abstraction), and external knowledge.
- iii) Bioinformatics: My work in this domain focuses on single-cell and multi-omics analysis, tackling key challenges such as representative cell selection (Nature Communications’25) and batch effect correction (TNNLS’23).

<!-- My research interests mainly focus on Multi-modal Learning and Multi-view Learning, especially the applications in open scenarios, e.g., missing modality and noisy correspondence. I am focusing on video-language currently. -->
<!-- For exceptional works and insights on noisy correspondence, I invite you to explore our repository [Noisy Correspondence Summary](https://github.com/XLearning-SCU/Awesome-Noisy-Correspondence). -->

I am currently seeking postdoctoral opportunities. If you have any advice or are interested in exploring academic collaborations, please feel free to contact me. I look forward to your insights and suggestions.

<!-- (sentence-visual pairs). -->

<!-- My research interests include Multimodal Learning and Unsupervised Learning, which can be unified to the framework of Representation Learning. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2025.01*: &nbsp; One paper about AI4Science was accepted by Nature Communications!
- *2024.12*: &nbsp; One paper about diffusion clustering was accepted by AAAI Conference on Artificial Intelligence. Congrats to Yuanyang.
- *2024.06*: &nbsp; We completed a comprehensive <a href="https://link.springer.com/content/pdf/10.1007/s44336-024-00001-w.pdf">survey on deep clustering</a> from the prior perspective. <a href="https://zhuanlan.zhihu.com/p/12059278751"><strong>中文简介</strong></a>
- *2024.04*: &nbsp; One paper was accepted by IEEE Transactions on Systems, Man and Cybernetics: Systems.
- *2024.01*: &nbsp; One paper was accepted by International Conference on Learning Representations (ICLR 2024) as  **oral**.
- *2023.12*: &nbsp; One paper was accepted by AAAI Conference on Artificial Intelligence (AAAI 2024). Congrats to Yiding.
<!-- - *2023.07*: &nbsp; One paper was accepted by International Conference on Computer Vision (ICCV 2023). -->
<!-- - *2022.10*: &nbsp; One paper was accepted at Findings of EMNLP 2022. -->
- *2022.08*: &nbsp; One paper was accepted by IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI).
<!-- - *2022.05*: &nbsp; One paper was accepted by IEEE Transactions on Image Processing  (TIP). -->
<!-- - *2021.03*: &nbsp; One paper was accepted by IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2021), Jun, 2021.  -->
<!-- Virtual-only Conference -->

# 📝 Publications 

\* Equal contribution <sup>†</sup> Corresponding author

<div class='paper-box'>
<div class='paper-box-image'><div>
<!-- <div class="badge">ICLR 2024</div> -->
<img src='assets/papers/llava-reid.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**ICML’25**</em>] [LLaVA-ReID: Selective Multi-image Questioner
for Interactive Person Re-Identification](https://arxiv.org/pdf/2504.10174) \\
Yiding Lu, Mouxing Yang, Dezhong Peng, Peng Hu, **Yijie Lin**<sup>†</sup>, Xi Peng<sup>†</sup>

<a href="https://github.com/XLearning-SCU/LLaVA-ReID"><strong>Code</strong></a>
<!-- \| -->
<!-- <a href="https://github.com/XLearning-SCU/2024-ICLR-Norton"><strong>Code</strong></a> -->
[![](https://img.shields.io/github/stars/XLearning-SCU/LLaVA-ReID?style=social&label=Stars)](https://github.com/XLearning-SCU/LLaVA-ReID)


<!-- <a href="https://mp.weixin.qq.com/s/yGieWt0s9jPPRX6sG03KDw"><strong>中文简介</strong></a> -->
<!-- \| -->
<!-- <a href="https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON"><strong>Code</strong></a> -->
<!-- [![](https://img.shields.io/github/stars/Lin-Yijie/Graph-Matching-Networks?style=social&label=Stars)](https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON) -->
<!-- <strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:Y0pCki6q_DkC'></span></strong> -->


- Introduce the first dialogue-based person re-identification task.

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
<img src='assets/papers/visa.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<em>**ICML'25**</em>] [Visual Abstraction: A Plug-and-Play Approach for Text-Visual Retrieval](https://pengxi.me/wp-content/uploads/2025/05/2025ICML.pdf), Guofeng Ding, Yiding Lu, Peng Hu, Mouxing Yang, **Yijie Lin**<sup>†</sup>, Xi Peng<sup>†</sup>

<a href="https://github.com/XLearning-SCU/2025-ICML-VISA"><strong>Code</strong></a> (Coming soon)
<!-- \| -->
<!-- <a href="https://github.com/XLearning-SCU/2024-ICLR-Norton"><strong>Code</strong></a> -->
<!-- [![](https://img.shields.io/github/stars/XLearning-SCU/2025-ICML-VISA?style=social&label=Stars)](https://github.com/XLearning-SCU/2025-ICML-VISA) -->


- Transform visual content into textual descriptions in a training-free manner
- A generative question-answer paradigm to enhance discriminative retrieval

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
<!-- <div class="badge">ICLR 2024</div> -->
<img src='assets/papers/norton.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[<em>**ICLR’24**</em>] [Multi-granularity Correspondence Learning from Long-term Noisy Videos](https://arxiv.org/pdf/2401.16702.pdf) \\
**Yijie Lin**, Jie Zhang, Zhenyu Huang, Jia Liu, Zujie Wen, Xi Peng

<span style="color:red">(Oral presentation, 1.2%)</span>
\|
<a href="https://mp.weixin.qq.com/s/q0kL62AM3G1wscTq92HIxA"><strong>中文简介</strong></a>
\|
<a href="https://iclr.cc/media/iclr-2024/Slides/19303.pdf"><strong>Slides</strong></a>
\|
<a href="https://iclr.cc/media/PosterPDFs/ICLR%202024/19303.png?t=1714532472.399705"><strong>Poster</strong></a>
\|
<a href="https://lin-yijie.github.io/projects/Norton/"><strong>Code</strong></a>
<!-- \| -->
<!-- <a href="https://github.com/XLearning-SCU/2024-ICLR-Norton"><strong>Code</strong></a> -->
[![](https://img.shields.io/github/stars/XLearning-SCU/2024-ICLR-Norton?style=social&label=Stars)](https://github.com/XLearning-SCU/2024-ICLR-Norton)



[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/multi-granularity-correspondence-learning-1/long-video-retrieval-background-removed-on)](https://paperswithcode.com/sota/long-video-retrieval-background-removed-on?p=multi-granularity-correspondence-learning-1)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/multi-granularity-correspondence-learning-1/zero-shot-video-retrieval-on-youcook2)](https://paperswithcode.com/sota/zero-shot-video-retrieval-on-youcook2?p=multi-granularity-correspondence-learning-1)

<!-- <a href="https://mp.weixin.qq.com/s/yGieWt0s9jPPRX6sG03KDw"><strong>中文简介</strong></a> -->
<!-- \| -->
<!-- <a href="https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON"><strong>Code</strong></a> -->
<!-- [![](https://img.shields.io/github/stars/Lin-Yijie/Graph-Matching-Networks?style=social&label=Stars)](https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON) -->
<!-- <strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:Y0pCki6q_DkC'></span></strong> -->


- Reveal multi-granularity noisy correspondence in long-term temporal modeling.

- Propose an efficient and robust video-language pre-training method.


</div>
</div>



<div class='paper-box'>

<div class='paper-box-image'><div>
<!-- <div class="badge">CVPR 2021, TPAMI 2022</div> -->
<img src='assets/papers/completer.jpg' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

<!-- [COMPLETER: Incomplete Multi-view Clustering via Contrastive Prediction](https://openaccess.thecvf.com/content/CVPR2021/papers/Lin_COMPLETER_Incomplete_Multi-View_Clustering_via_Contrastive_Prediction_CVPR_2021_paper.pdf) \\ -->
[<em>**CVPR’21**</em>] [COMPLETER: Incomplete Multi-view Clustering via Contrastive Prediction](http://pengxi.me/wp-content/uploads/2021/03/2021CVPR-completer.pdf) \\
 **Yijie Lin**, Yuanbiao Gou, Zitao Liu, Boyun Li, Jiancheng Lv, Xi Peng


<a href="https://www.bilibili.com/video/BV1Ub4y1a7Zy?spm_id_from=333.337.search-card.all.click&vd_source=c4896e9b68d2c7a283fe99a0899df781"><strong>Video</strong></a>
\|
<a href="https://cs.scu.edu.cn/info/1246/15640.htm"><strong>中文简介</strong></a>
\|
<a href="https://github.com/XLearning-SCU/2021-CVPR-Completer"><strong>Code</strong></a>
<!-- **Code**  -->
[![](https://img.shields.io/github/stars/XLearning-SCU/2021-CVPR-Completer?style=social&label=Stars)](https://github.com/XLearning-SCU/2021-CVPR-Completer)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:d1gkVwhDpl0C'></span></strong>
<!-- https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=KXKVYHsAAAAJ:d1gkVwhDpl0C -->


[<em>**TPAMI’22**</em>] [Dual Contrastive Prediction for Incomplete Multi-view Representation Learning](http://pengxi.me/wp-content/uploads/2023/02/DCP-2023_compressed.pdf) \\
**Yijie Lin**, Yuanbiao Gou, Xiaotian Liu, Jinfeng Bai, Jiancheng Lv, Xi Peng

<a href="https://cs.scu.edu.cn/info/1246/17111.htm"><strong>中文简介</strong></a>
\|
<a href="https://github.com/XLearning-SCU/2022-TPAMI-DCP"><strong>Code</strong></a>
[![](https://img.shields.io/github/stars/XLearning-SCU/2022-TPAMI-DCP?style=social&label=Stars)](https://github.com/XLearning-SCU/2022-TPAMI-DCP)
<strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:UeHWp8X0CEIC'></span></strong>
</div>

</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
<!-- <div class="badge">ICCV 2023</div> -->
<img src='assets/papers/common.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<em>**ICCV’23**</em>] [Graph Matching with Bi-level Noisy Correspondence](https://arxiv.org/pdf/2212.04085) \\
**Yijie Lin**, Mouxing Yang, Jun Yu, Peng Hu, Changqing Zhang, Xi Peng

<a href="https://www.bilibili.com/video/BV1gH4y1H7MQ/?spm_id_from=333.337.search-card.all.click&vd_source=c4896e9b68d2c7a283fe99a0899df781"><strong>Video</strong></a>
\|
<a href="https://mp.weixin.qq.com/s/yGieWt0s9jPPRX6sG03KDw"><strong>中文简介</strong></a>
\|
<a href="https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON"><strong>Code</strong></a>
<!-- **Code**  -->
[![](https://img.shields.io/github/stars/Lin-Yijie/Graph-Matching-Networks?style=social&label=Stars)](https://github.com/Lin-Yijie/Graph-Matching-Networks/tree/main/COMMON)
<strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:Y0pCki6q_DkC'></span></strong>

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/graph-matching-with-bi-level-noisy/graph-matching-on-spair-71k)](https://paperswithcode.com/sota/graph-matching-on-spair-71k?p=graph-matching-with-bi-level-noisy)
- Reveal bi-level (node- and edge-level) noisy correspondence challenge. 
- This work is included by famous open-source graph matching project [ThinkMatch](https://GitHub.com/Thinklab-SJTU/ThinkMatch/)
[![GitHub stars](https://img.shields.io/github/stars/Thinklab-SJTU/ThinkMatch.svg?style=social&label=Star&maxAge=8640)](https://GitHub.com/Thinklab-SJTU/ThinkMatch/)

</div>
</div>


<!-- - `TPAMI 2022` [Dual Contrastive Prediction for Incomplete Multi-view Representation Learning](http://pengxi.me/wp-content/uploads/2023/02/DCP-2023_compressed.pdf),  **Yijie Lin**, Yuanbiao Gou, Xiaotian Liu, Jinfeng Bai, Jiancheng Lv, Xi Peng
\|
<a href="https://cs.scu.edu.cn/info/1246/17111.htm"><strong>中文简介</strong></a>
\|
<a href="https://github.com/XLearning-SCU/2022-TPAMI-DCP"><strong>Code</strong></a> -->




- [<em>**Nature Communications'25**</em>] [MetaQ: fast, scalable and accurate metacell inference via single-cell quantization](https://www.nature.com/articles/s41467-025-56424-6.pdf), Yunfan Li, Hancong Li, **Yijie Lin**, Dan Zhang, Dezhong Peng, Xiting Liu, Jie Xie, Peng Hu, Lu Chen,  Han Luo, Xi Peng
\| <a href="https://github.com/XLearning-SCU/MetaQ"><strong>Code</strong></a>


- [<em>**AAAI'25**</em>] [Incomplete Multi-view Clustering via Diffusion Contrastive Generation](https://arxiv.org/pdf/2503.09185), Yuanyang Zhang\*, **Yijie Lin**\*, Weiqing Yan, Li Yao, Xinhang Wan, Guangyuan Li, Chao Zhang, Guanzhou Ke, Jie Xu
\| <a href="https://github.com/zhangyuanyang21/2025-AAAI-DCG"><strong>Code</strong></a>



- [<em>**NeurIPS'24**</em>] [Robust Contrastive Multi-view Clustering against Dual Noisy Correspondence](http://pengxi.me/wp-content/uploads/2024/11/Robust_Contrastive_Multi-view_Clustering_against_Dual_Noisy_Correspondence.pdf), Ruiming Guo, Mouxing Yang, **Yijie Lin**, Xi Peng,  Peng Hu 
\| <a href="https://github.com/XLearning-SCU/2024-NeurIPS-CANDY"><strong>Code</strong></a>

- [<em>**AAAI'24**</em>] [Decoupled Contrastive Multi-view Clustering with High-order Random Walks](https://arxiv.org/pdf/2308.11164.pdf), Yiding Lu, **Yijie Lin**, Mouxing Yang, Dezhong Peng, Peng Hu, Xi Peng \| <a href="https://github.com/XLearning-SCU/2024-AAAI-DIVIDE"><strong>Code</strong></a>
<!-- [![](https://img.shields.io/github/stars/XLearning-SCU/2024-AAAI-DIVIDE?style=social&label=Stars)](https://github.com/XLearning-SCU/2024-AAAI-DIVIDE) -->

- [<em>**Vicinagearth'24**</em>] [A survey on deep clustering: from the prior perspective](https://link.springer.com/content/pdf/10.1007/s44336-024-00001-w.pdf), Yiding Lu, Haobin Li, Yunfan Li, **Yijie Lin**, Xi Peng \| <a href="https://zhuanlan.zhihu.com/p/12059278751"><strong>中文简介</strong></a>


- [<em>**TSMC'24**</em>] [UNITE: Multitask Learning With Sufficient Feature for Dense Prediction](https://ieeexplore.ieee.org/document/10534190), Yuxin Tian, **Yijie Lin**, Qing Ye, Jian Wang, Xi Peng, Jiancheng Lv  \| <a href="https://github.com/slyviacassell/Multi-task-UNITE"><strong>Code</strong></a>

- [<em>**TNNLS'23**</em>] [Single-cell RNA-seq Debiased Clustering via Batch Effect Disentanglement](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10086540), Yunfan Li, **Yijie Lin**, Han Luo, Peng Hu, Dezhong Peng, Xi Peng  \| <a href="https://github.com/Yunfan-Li/SCDC"><strong>Code</strong></a>


- [<em>**EMNLP Findings'22**</em>] [Improve Interpretability of Neural Networks via Sparse Contrastive Coding](https://aclanthology.org/2022.findings-emnlp.32.pdf), Junhong Liu\*,
**Yijie Lin**\*, Liang Jiang, Jia Liu, Zujie Wen, Xi Peng

- [<em>**TIP'22**</em>] [Unsupervised Neural Rendering for Image Hazing](https://ieeexplore.ieee.org/document/9788526/), Boyun Li, **Yijie Lin**, Xiao Liu, Peng Hu, Jiancheng Lv, Xi Peng

<!-- Tech Report -->


<!-- under review -->

# 🎖 Honors and Awards
- *2024.12* Tencent Scholarship (Outstanding award at SCU)
- *2023.10* National Scholarship (PhD student)
- *2022.11* [Huawei Scholarship](https://ygb.scu.edu.cn/info/1007/2515.htm) (First prize at SCU)  
<!-- at Sichuan University -->
<!-- - *2021.10* Innovation Scholarship (PhD student)  -->
- *2019.09* [National Scholarship](http://www.moe.gov.cn/srcsite/A05/s7505/201912/t20191217_412368.html) (Undergraduate, Top 1%)


<!-- # 📖 Educations
- 2020.09 - now, Ph.D. student, Sichuan Univeristy, Chengdu.
- 2016.09 - 2020.06, Undergraduate, Sichuan Univeristy, Chengdu. -->


<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)


# 💻 
-->
# 🙋 Service
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China.  -->

<!-- - Journal Reviewer of IEEE Transactions on Knowledge and Data Engineering, IEEE Transactions on Neural Networks and Learning Systems, IEEE Transactions on Systems, Man and Cybernetics: Systems. -->
- **Journal Reviewer**: IEEE TIP, IEEE TKDE, IEEE TNNLS, IEEE TAI, and more.
<!-- IEEE TCYB, IEEE TAI, IEEE TSMC, Machine Learning, Neural Networks, and more. -->

- **Conference Reviewer**: ICLR, NeurIPS, ICML, CVPR, ICCV, ECCV, ACL, AAAI, ACMMM, and more.
<!-- - Conference Reviewer: of ICLR 2023, NeurIPS 2023, ICML 2023, ICCV 2023, AAAI 2023. -->
<!-- , CICAI 2021-2022, ICIG 2021, ACML 2021, PRCV 2021-2022 -->

<!-- 
# 💬 Talks ~
 -->

