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

I am a Researcher in the [Zhejiang University, Schoolof Software Technology](http://www.cst.zju.edu.cn/) <img src='./images/ZJU-Logo.png' style='width: 6em;'>. Before coming to ZJU, I worked at [Huawei, 2012 Lab](https://www.huawei.com/en/) <img src='./images/Huawei-Logo.wine.png' style='width: 5em;'> as a Senior Engineer. I graduated from Department of Computer Science and Technology, Zhejiang University with a Ph.D. degreed. 

My research interests lie in system security, intrustion detection and cyber threat analysis techniques. I am now working towards to design practical intrusion detection and attack investigation systems. Currently I work closely with [Prof. Yan Chen](https://users.cs.northwestern.edu/~ychen/).

**"Contact [me](mailto:li_zhenyuan@qq.com) for intrusion detection systems research that are in line with the industry!!!"（持续招收对安全研究有兴趣的硕士研究生和本科生！）**


# 🔥 News
- *2023.06*: &nbsp;🎉🎉 I join [Zhejiang University, Schoolof Software Technology](http://www.cst.zju.edu.cn/) <img src='./images/ZJU-Logo.png' style='width: 6em;'> as Researcher. 


# 💫 Fundings
- 国家重点研发计划，**面向终端的高隐蔽传播网络公害识别，取证和归因研究**，2024/01-2026/12，在研，子课题负责人
- “蚂蚁”校企合作项目，**基于大语言模型的自动化漏洞利用方案生成与推荐**，2024/06-2025/06，在研，项目负责人
- “华为”校企合作项目，**抗混淆的鸿蒙应用安全指纹与风险描述生成算法研究**，2024/06-2025/06，在研，课题负责人
- 浙江省“领雁”研发计划，**某云平台安全技术研究**，2024/01-2024/12，在研，课题负责人
- CCF-绿盟“鲲鹏”科研基金，**云计算环境下基于流处理的大规模溯源分析**，2024/01-2024/12，在研，项目负责人


# 📝 Publications 
- ``ArXiv 2024`` [Marlin: Knowledge-Driven Analysis of Provenance Graphs forEfficient and Robust Detection of Cyber Attacks](https://arxiv.org/pdf/2403.12541), **Zhenyuan Li**, Yangyang Wei, Xiangmin Shen, Lingzhi Wang, Yan Chen, Haitao Xu, Shouling Ji, Fan Zhang, Liang Hou, Wenmao Liu, Xuhong Zhang, Jianwei Ying

- ``ArXiv 2024`` [Incorporating Gradients to Rules: Towards Lightweight, Adaptive Provenance-based Intrusion Detection](https://arxiv.org/pdf/2404.14720), Lingzhi Wang, Xiangmin Shen, Weijian Li, **Zhenyuan Li**, R Sekar, Han Liu, Yan Chen

- ``AsiaCCS 2024`` [Decoding the MITRE Engenuity ATT&CK Enterprise Evaluation: An Analysis of EDR Performance in Real-World Environments](https://dl.acm.org/doi/pdf/10.1145/3634737.3645012), Xiangmin Shen, **Zhenyuan Li**, Graham Burleigh, Lingzhi Wang, Yan Chen

- ``CSCWD 2024`` [An Automated Alert Cross-Verification System with Graph Neural Networks for IDS Events](https://ieeexplore.ieee.org/abstract/document/10580010/), Liang Li, Yuanhui He, Feiyang Huang, Ziming Zhao, Zhuoxue Song, Tong Zhou, **Zhenyuan Li**, Fan Zhang

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESORICS 2022</div><img src='images/AttacKG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AttacKG: Constructing Technique Knowledge Graph from Cyber Threat Intelligence Reports](https://link.springer.com/chapter/10.1007/978-3-031-17140-6_29)

**Zhenyuan Li**, Jun Zeng, Yan Chen, Zhenkai Liang

[**Project**](https://github.com/li-zhenyuan/Knowledge-enhanced-Attack-Graph) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:UeHWp8X0CEIC'></span></strong> 
![](https://img.shields.io/github/stars/li-zhenyuan/Knowledge-enhanced-Attack-Graph?style=social)

- AttacKG can automatically extract structured attack behavior graphs from CTI reports and identify the associated attack techniques, and aggregate threat intelligence across reports to collect different aspects of techniques and enhance attack behavior graphs into technique knowledge graphs (TKGs).
- AttacKG can empower many downstream security applications such as **threat identification**, **automatic threat reasoning and disposition**.
</div>
</div>

- ``TDSC 2022`` [RATScope: Recording and Reconstructing Missing RAT Semantic Behaviors for Forensic Analysis on Windows](https://ieeexplore.ieee.org/document/9234076), Runqing Yang, Xutong Chen, Haitao Xu, Yueqiang Chen, Chunlin Xiong, Linqi Ruan, Mohammad Kavousl, **Zhenyuan Li**, Liheng Xu, Yan Chen 

- ``NDSS 2022 Poster`` [Poster: Towards automated and large-scale cyber attack reconstruction with apt reports](https://www.ndss-symposium.org/wp-content/uploads/NDSS2022Poster_paper_37.pdf), Chunlin Xiong, **Zhenyuan Li**, Yan Chen, Tiantian Zhu, Jian Wang, Hai Yang, Wei Ruan

- ``FITEE 2022`` [Generic, Efficient, and Effective Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts](https://link.springer.com/article/10.1631/FITEE.2000436), Chunlin Xiong, **Zhenyuan Li**, Qi Alfred Chen, Yan Chen, Tiantian Zhu, Hai Yang, and Wei Ruan

- ``COSE 2021`` [Threat Detection and Investigation with System-level Provenance Graphs: A Survey](https://www.sciencedirect.com/science/article/pii/S0167404821001061), **Zhenyuan Li**, Qi Alfred Chen, Yang Runqing, Yan Chen

- ``ACSAC 2020 Poster`` [Poster: Mimic the Whole Attack Chain: A First Look at Evasion against Provenance Graph based Detection](https://www.researchgate.net/profile/Zhenyuan-Li-3/publication/346655029_Mimic_the_Whole_Attack_Chain_A_First_Look_at_Evasion_against_Provenance_Graph_based_Detection/links/5fce220945851568d146d3ef/Mimic-the-Whole-Attack-Chain-A-First-Look-at-Evasion-against-Provenance-Graph-based-Detection.pdf), **Zhenyuan Li**, Qi Alfred Chen, Yang Runqing, Yan Chen

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2019</div><img src='images/CCS19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Effective and Light-Weight Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts](https://dl.acm.org/doi/10.1145/3319535.3363187)

**Zhenyuan Li**, Qi Alfred Chen, Chunlin Xiong, Yan Chen, Tiantian Zhu, Hai Yang

[**Project**](https://github.com/li-zhenyuan/Effective-and-Light-Weight-Deobfuscation-and-Semantic-Aware-Attack-Detection-for-PowerShell-Scripts) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:u-x6o8ySG0sC'></span></strong>
![](https://img.shields.io/github/stars/li-zhenyuan/Effective-and-Light-Weight-Deobfuscation-and-Semantic-Aware-Attack-Detection-for-PowerShell-Scripts?style=social)

- The first effective and light-weight deobfuscation approach for PowerShell scripts. Adopted in the product of an [startup security company](https://www.fyreshld.com/) <img src='./images/MingYan.jpg' style='width: 4em;'>.
</div>
</div>


# 🎖 Honors and Awards
- *2021.02* Zhejiang Lab's International Talent Fund for Young Professionals
- *2020-12* Zhejiang University's Academic Rising Star 
- *2017-05* Outstanding Graduate of Xidian University (Top 1%)
- *2015-11* National Scholarship (Undergraduate) (Top 1%)


# 📖 Educations
- *2017.09 - 2022.06*, Ph.D. in Cyber Security, Zhejiang University, Advised by [Prof. Yan Chen](https://users.cs.northwestern.edu/~ychen/).
- *2021.05 - 2022.04*, Visiting Ph.D. Student, National University of Singapore, Advised by [Prof. Zhenkai Liang](https://www.comp.nus.edu.sg/~liangzk/).
- *2015.09 - 2019.06*, B.S. in Information Security, Xidian University. 
- *2010.09 - 2013.06*, Zhenhai Middle School, Ningbo.


# 💬 Invited Talks
- *2020.10*, InForSec Cyber Security Academic Papers Sharing (Co-located with Beijing Cyber Security Conference)  \| [\[video\]](https://www.bilibili.com/video/BV1gy4y187Lq/?share_source=copy_web&vd_source=23dc4357b22105e2ec9569d56ca4163c)
- *2019.11*, Effective and Light-Weight Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts, CCS'19, London


# 💻 Work Experience
- *2023.07 - now*, [Zhejiang University](https://www.zju.edu.cn), Hangzhou, China.
- *2022.07 - 2023.07*, [Huawei, 2012 Lab](https://www.huawei.com/en/), Hangzhou, China.


# 🎓 Academic Service
- Subreviewer/External reviewer : NDSS'22, AsiaCCS'21, CCS'19, ICDCS'19, ESORICS'19, CCS'18
- Reviewer : TOSEM (2024), 计算机学报 (2024), 计算机科学(2024), IEEE Access (2020)
