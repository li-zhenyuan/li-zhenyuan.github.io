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

I am a Researcher at the [School of Software Technology, Zhejiang University](http://www.cst.zju.edu.cn/) <img src='./images/ZJU-Logo.png' style='width: 6em; vertical-align: middle;'>. Before joining ZJU, I worked at [Huawei 2012 Lab](https://www.huawei.com/en/) <img src='./images/Huawei-Logo.wine.png' style='width: 5em; vertical-align: middle;'> as a Senior Engineer. I received my Ph.D. degree from the Department of Computer Science and Technology at Zhejiang University.

My research interests lie in **system security**, **intrusion detection**, and **cyber threat analysis**. My current work focuses on designing practical intrusion detection and attack investigation systems. I work closely with Prof. [Shouling Ji](https://nesa.zju.edu.cn), Prof. Fan Zhang from Zhejiang University and Prof. [Yan Chen](https://users.cs.northwestern.edu/~ychen/) from Northwestern University,.

<!-- **Research Map:**
<img src='images/李振源-2025年ACES暑期工作会议_05.png' alt="sym" width="86%"> -->

**Recent research interests include:**
- Intelligent yet Effcient Cyber Attack Hunting
- Automatic Penetration and Attack Planning
- Action Security for LLM Agents

Feel free to [contact me](mailto:li_zhenyuan@qq.com) if you are interested in industry-oriented security research.（**招收2026级硕士生4-5名, 欢迎联系！**）


# 🔥 News
- 🧑‍💻 *2025.12*, Invited to serve as an TPC member for "GlobalCom 2026 CISS". 
- 🧑‍💻 *2025.12*, Invited to serve as an Early Career Editorial Board member for the journal "Digital Twins and Applications". 
- 📑 *2025.11*, Our paper "Actionable, Customizable, and Causality-Preserving Cyberattack Emulation with LLM-powered Symbolic Planning" is accepted by ACNS'26.
- 🏗️ *2025.11*, Granted Natural Science Foundation of Ningbo (Youth Ph.D Program) as PI.
- 📑 *2025.11*, Our paper "[Breaking the Bulkhead: Demystifying Cross-Namespace Reference Vulnerabilities in Kubernetes Operators](https://arxiv.org/pdf/2507.03387)" is accepted by NDSS'26.
- 📑 *2025.10*, Our paper "[Towards Scalable and Interpretable Mobile App Risk Analysis via Large Language Models](https://arxiv.org/pdf/2508.15606)" is accepted by ICSE'26.
- 📑 *2025.09*, Our paper "[Incorporating Gradients to Rules: Towards Online, Adaptive Provenance-based Intrusion Detection](https://ieeexplore.ieee.org/abstract/document/11169421/)" is accepted by TDSC.
- 🏗️ *2025.07*, Granted CCF-Tencent "Rhino-Bird" Open Research Fund as PI.
- 📑 *2025.07*, Our paper "Learning in Provenance-Based Intrusion Detection: A Survey" accepted by Chinese Journal of Computers.
- 📑 *2025.05*, Our paper "[The Case for Learned Provenance-based System Behavior Baseline](https://openreview.net/pdf?id=SY4owu5BK6)" is accepted by ICML'25.
- 📑 *2025.04*, One paper "[PentestAgent: Incorporating LLM Agents to Automated Penetration Testing](https://dl.acm.org/doi/pdf/10.1145/3708821.3733882)" is accepted by AsiaCCS'25.
- 🧑‍💻 *2025.03*, Invited to serve as an TPC member for "GlobalCom 2025 CISS". 
- 🎉 *2024.09*, Awarded Ningbo "YongJiang" Talent Programme (Youth Program).
- 🏗️ *2024.08*, Granted National Natural Science Foundation of China (Youth Program) as PI.
- 📑 *2024.08*, Our paper "Incorporating Gradients to Rules: Towards Lightweight, Adaptive Provenance-based Intrusion Detection" is accepted by NDSS'25.

<!-- - 🎉 *2025.12*, Awarded First Prize in the Science and Technology Progress Award by "China General Chamber of Commerce" \(ranked 5/15\) -- "Key Technologies and Industrial Applications of AI-Driven Cybersecurity Detection." -->
<!-- - 🎉 *2025.09*, Awarded Second Prize of the Beijing Municipal Science and Technology Progress Award \(ranked 7/10\) -- "Key Technologies and Applications for Detection and Attribution of Highly Stealthy Cyber Threats Based on Anti-Stealth Mechanisms". -->
<!-- - 📑 *2025.07*, Our paper "AutoSeg: Automatic Micro-segmentation Policy Generation via Configuration Analysis" is accepted by Computer & Security. -->
<!-- - 🏗️ *2024.12*, Granted "Leading Goose" R&D Program of Zhejiang as PI. -->
<!-- - 📑 *2024.12*, One paper "Understanding the Business of Online Affiliate Marketing: An Empirical Study" is accepted by INFOCOM'25. -->
<!-- - 📑 *2024.01*, One paper "Decoding the MITRE Engenuity ATT&CK Enterprise Evaluation: An Analysis of EDR Performance in Real-World Environments" is accepted by AsiaCCS'24. -->

<!-- - 📑 *2025.09*, Our paper "Mobile Platform Spyware Prevention: Insights, Challenges, and Outlook" accepted by the Journal of Cybersecurity (Chinese) -->
<!-- - 🎉 *2025.05*, The student project "Chongming Niao: An Online Detection System for Highly Stealthy Threats in Massive Log Streams" won the National Second Prize in the Software Innovation Competition – Software System Security Track, along with the "Outstanding Faculty Advisor Award.” Congratulations to the participating students! \[[Link](http://www.ccsssc.com/notice)\] -->
<!-- - 📃 *2025.02*, One poster "[LLM-Driven Automated Exploit Assessment for Penetration Testing](https://ndss25-posters.hotcrp.com/u/0/doc/ndss25-posters-final71.pdf)" will appear in NDSS'25 poster session. -->


# 🛠️ Projects
- Automated Penetration Testing
- [Aurora: Automated Cyberattack Emulation](https://github.com/LexusWang/Aurora-demos?tab=readme-ov-file)
- [Marlin: Streaming Provenance Graph Analysis](https://github.com/MarineYY/MARLIN)


# 📝 Selected Publications 

**Full List: [Google Scholar](https://scholar.google.com/citations?user=3YGMOdwAAAAJ)** 
(* Equally Contribution, # Corresponding Author)

#### [Conference Papers]

[C10] ``ACNS 2026`` "Actionable, Customizable, and Causality-Preserving Cyberattack Emulation with LLM-powered Symbolic Planning", Lingzhi Wang, **Zhenyuan Li**, Yi Jiang, Zhengkai Wang, Xiangmin Shen, Wei Ruan, Yan Chen 

[C9] ``ICSE 2026`` "[Towards Scalable and Interpretable Mobile App Risk Analysis via Large Language Models](https://arxiv.org/pdf/2508.15606)", Yu Yang\*, **Zhenyuan Li\*#**, Xiandong Ran, Jiahao Liu, Jiahui Wang, Bo Yu, Shouling Ji 

[C8] ``NDSS 2026`` "[Breaking the Bulkhead: Demystifying Cross-Namespace Reference Vulnerabilities in Kubernetes Operators](https://arxiv.org/pdf/2507.03387)", Andong Chen, Ziyi Guo, Zhaoxuan Jin, **Zhenyuan Li#**, Yan Chen 

[C7] ``ICML 2025`` "[The Case for Learned Provenance-based System Behavior Baseline](https://openreview.net/pdf?id=SY4owu5BK6)", Yao Zhu\*, **Zhenyuan LI\*#**, Yangyang Wei, Shouling Ji  

[C6] ``AsiaCCS 2025`` "[PentestAgent: Incorporating LLM Agents to Automated Penetration Testing](https://dl.acm.org/doi/pdf/10.1145/3708821.3733882)", Xiangmin Shen, Lingzhi Wang, **Zhenyuan Li**, Yan Chen, Wencheng Zhao, Dawei Sun, Jiashui Wang, Wei Ruan

[C5] ``NDSS 2025`` "[Incorporating Gradients to Rules: Towards Lightweight, Adaptive Provenance-based Intrusion Detection](https://arxiv.org/pdf/2404.14720)", Lingzhi Wang, Xiangmin Shen, Weijian Li, **Zhenyuan Li#**, R Sekar, Han Liu, Yan Chen

[C4] ``INFOCOM 2025`` "Understanding the Business of Online Affiliate Marketing: An Empirical Study", Haitao Xu, Yiwen Sun, Kaleem Ullah Qasim, Shuai Hao, Wenrui Ma, **Zhenyuan Li**, Fan Zhang, Meng Han, Zhao Li

[C3] ``AsiaCCS 2024`` "[Decoding the MITRE Engenuity ATT&CK Enterprise Evaluation: An Analysis of EDR Performance in Real-World Environments](https://dl.acm.org/doi/pdf/10.1145/3634737.3645012)", Xiangmin Shen, **Zhenyuan Li**, Graham Burleigh, Lingzhi Wang, Yan Chen


[C2] ``ESORICS 2022`` "[AttacKG: Constructing Technique Knowledge Graph from Cyber Threat Intelligence Reports](https://link.springer.com/chapter/10.1007/978-3-031-17140-6_29)", **Zhenyuan Li**, Jun Zeng, Yan Chen, Zhenkai Liang

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESORICS 2022</div><img src='images/AttacKG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[AttacKG: Constructing Technique Knowledge Graph from Cyber Threat Intelligence Reports](https://link.springer.com/chapter/10.1007/978-3-031-17140-6_29)"

**Zhenyuan Li**, Jun Zeng, Yan Chen, Zhenkai Liang

[**Project**](https://github.com/li-zhenyuan/Knowledge-enhanced-Attack-Graph) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:UeHWp8X0CEIC'></span></strong> 
![](https://img.shields.io/github/stars/li-zhenyuan/Knowledge-enhanced-Attack-Graph?style=social)

- AttacKG can automatically extract structured attack behavior graphs from CTI reports and identify the associated attack techniques, and aggregate threat intelligence across reports to collect different aspects of techniques and enhance attack behavior graphs into technique knowledge graphs (TKGs).
- AttacKG can empower many downstream security applications such as **threat identification**, **automatic threat reasoning and disposition**.
</div>
</div> -->

<!-- - ``CCS 2019`` "[Effective and Light-Weight Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts](https://dl.acm.org/doi/10.1145/3319535.3363187)", **Zhenyuan Li**, Qi Alfred Chen, Chunlin Xiong, Yan Chen, Tiantian Zhu, Hai Yang -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2019</div><img src='images/CCS19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[Effective and Light-Weight Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts](https://dl.acm.org/doi/10.1145/3319535.3363187)"

**Zhenyuan Li**, Qi Alfred Chen, Chunlin Xiong, Yan Chen, Tiantian Zhu, Hai Yang

[**Project**](https://github.com/li-zhenyuan/Effective-and-Light-Weight-Deobfuscation-and-Semantic-Aware-Attack-Detection-for-PowerShell-Scripts) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:u-x6o8ySG0sC'></span></strong>
![](https://img.shields.io/github/stars/li-zhenyuan/Effective-and-Light-Weight-Deobfuscation-and-Semantic-Aware-Attack-Detection-for-PowerShell-Scripts?style=social)

- The first effective and light-weight deobfuscation approach for PowerShell scripts. Adopted in the product of an [startup security company](https://www.fyreshld.com/) <img src='./images/MingYan.jpg' style='width: 4em;'>.
</div>
</div>


#### [Journal Papers]
[J7] ``Microelectronics & Computer (in Chinese)`` "Analysis, Description, and Reproduction Methods for Attack Processes Driven by Large Language Models", Jin Qian, Shiyu Tan, Libin Xu, Jun Luo, **Zhenyuan Li#**

[J6] ``TDSC 2025`` "[Incorporating Gradients to Rules: Towards Online, Adaptive Provenance-based Intrusion Detection](https://ieeexplore.ieee.org/abstract/document/11169421/)", **Zhenyuan Li#**, Lingzhi Wang, Zhengkai Wang, Xiangmin Shen, Haitao Xu, Yan Chen, Shouling Ji 

<!-- - ``计算机学报`` "智能溯源分析与入侵检测：洞察、挑战与展望”, **李振源**, 韦洋洋, 王征凯, 纪守领 -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Chinese Journal of Computers</div><img src='images/溯源分析框架.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"Learning in Provenance-Based Intrusion Detection: A Survey"

**Zhenyuan Li**, Yangyang Wei, Zhengkai Wang, Shouling Ji

- The ability of machine learning models to discover and represent features offers new insights and solutions for accurately and efficiently extracting attack patterns, thereby improving the precision of provenance-based detection. Moreover, advances in efficient data compression and indexing enable faster analysis and significantly reduce computational overhead.

</div>
</div>

[J4] ``Journal of Cyber Security (in Chinese)`` "Mobile Spyware and Its Detection: A Survey", Yi Jiang, Zhenyuan Li#, Fan Zhang, Yixin Jiang, Wenqian Xu, and Zhihong Liang.

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/aurora.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[From Sands to Mansions: Towards Automated Cyberattack Emulation with Classical Planning and Large Language Models](https://arxiv.org/pdf/2407.16928)"

Lingzhi Wang, **Zhenyuan Li#**, Yi Jiang, Zhengkai Wang, Zonghan Guo, Jiahui Wang, Yangyang Wei, Xiangmin Shen, Ruan Wei, Yan Chen

[**Project**](https://github.com/LexusWang/Aurora-demos?tab=readme-ov-file) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:UeHWp8X0CEIC'></span></strong> 
![](https://img.shields.io/github/stars/LexusWang/Aurora-demos?style=social)

- AURORA leverages a modular attack model and LLM to automatically generate and execute complex cyberattacks, aiming to create a large-scale, realistic dataset for enhancing cyber defense. By automating attack planning, environment setup, and semi-automatic execution, AURORA successfully constructed a dataset of over 1,000 attack chains.

</div>
</div> -->

[J3] ``COSE 2025`` "[AutoSeg: Automatic Micro-segmentation Policy Generation via Configuration Analysis](https://www.sciencedirect.com/science/article/abs/pii/S0167404825002809)", Andong Chen, Zhaoxuan Jin, **Zhenyuan Li#**, Yan Chen, Yu Ning, Ying Wang 
  
[J2] ``TDSC 2022`` "[RATScope: Recording and Reconstructing Missing RAT Semantic Behaviors for Forensic Analysis on Windows](https://ieeexplore.ieee.org/document/9234076)", Runqing Yang, Xutong Chen, Haitao Xu, Yueqiang Chen, Chunlin Xiong, Linqi Ruan, Mohammad Kavousl, **Zhenyuan Li**, Liheng Xu, Yan Chen 

[J1] ``COSE 2021`` "[Threat Detection and Investigation with System-level Provenance Graphs: A Survey](https://www.sciencedirect.com/science/article/pii/S0167404821001061)", **Zhenyuan Li**, Qi Alfred Chen, Yang Runqing, Yan Chen


#### [Workshop/ArXiv/Other Papers]

<!-- - ``ArXiv`` "[Marlin: Knowledge-Driven Analysis of Provenance Graphs forEfficient and Robust Detection of Cyber Attacks](https://arxiv.org/pdf/2403.12541)",  **Zhenyuan Li**, Yangyang Wei, Xiangmin Shen, Lingzhi Wang, Yan Chen, Haitao Xu, Shouling Ji, Fan Zhang, Liang Hou, Wenmao Liu, Xuhong Zhang, Jianwei Ying -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2024</div><img src='images/Marlin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[Marlin: Knowledge-Driven Analysis of Provenance Graphs forEfficient and Robust Detection of Cyber Attacks](https://arxiv.org/pdf/2403.12541)"

**Zhenyuan Li**, Yangyang Wei, Xiangmin Shen, Lingzhi Wang, Yan Chen, Haitao Xu, Shouling Ji, Fan Zhang, Liang Hou, Wenmao Liu, Xuhong Zhang, Jianwei Ying

[**Project**](https://github.com/MarineYY/MARLIN) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:UeHWp8X0CEIC'></span></strong> 
![](https://img.shields.io/github/stars/MarineYY/MARLIN?style=social)

- Marlin conceptualize real-time attack detection in streaming logs as a streaming graph alignment problem, leveraging query graphs to pinpoint critical elements in the provenance graph. Integrated into a tag propagation framework, it processes each event once, reducing redundancy and enhancing efficiency and defense against evasion.
    
</div>
</div>


# 📑 Selected Patents
- **Comprehensive Data Collection:**
(Patent Application Filed) Fine-Grained Provenance Data Collection Method and Apparatus for Android Systems Based on eBPF
(Patent Granted) Fine-Grained Provenance Data Collection Method and System for Cloud Platforms Based on Multi-Layer Data Fusion

- **Efficient Threat Hunting:**
(Patent Granted) Real-Time Attack Chain Detection Method and System Based on Label Propagation and Event Baseline Learning
(Patent Granted) Real-Time Attack Detection Method and System for Streaming Provenance Graphs Based on Labeling and Graph Alignment
(Patent Application Filed) Suspicious Event Forward-Backward Tracing and Attack Path Reconstruction Method and System Based on Large Models
(Patent Application Filed) Application Risk Assessment Method and Apparatus Based on Large Model Multi-Agent Decision Trees

- **Intelligent Rule Optimization:**
(Patent Granted) Anomaly Detection Method and System for Streaming Provenance Graphs Based on Iterative Prediction-Correction
(Patent Granted) Attack Detection Policy Optimization Method and System Based on Feature Backpropagation

- **Automated Attack Planning:**
(Patent Application Filed) An End-to-End Network Attack Construction Method
(Patent Application Filed) Multi-Stage Automated Penetration Testing Plan Generation Method and System Based on Large Language Models and Attack Tree Models



# 💫 Selected Fundings
- National Natural Science Foundation of China (Youth Program), **Research on Methods and Key Technologies for Large-Scale Real-Time Attack Detection and Attribution**, 2024/01-2026/12, Ongoing, PI
- National Key R&D Program of China – “Cyberspace Security Governance” Special Project, **Terminal-Oriented Identification, Forensics, and Attribution of Highly Stealthy Propagation-Based Cyber Nuisances**, , Ongoing, Sub-Task Leader
- Zhejiang Provincial Key R&D Program \("Leading Goose"\), **\*\*\*\*\*\***, 2025/01-2025/12, Ongoing, PI
- Zhejiang Provincial Key R&D Program \("Leading Goose"\), **\*\*\*\*\*\***, 2024/01-2024/12, Ongoing, Task Leader
- Ningbo "Yongjiang" Young Innovative Talents Project, **\*\*\*\*\*\***, 2025/01-2027/12, Ongoing, PI
- Natural Science Foundation of Ningbo – Young Doctoral Innovation Research Project, **Behavior Governance and Security Protection for Emerging Heterogeneous Systems in Critical Infrastructure**, 2026/01-2027/12, Ongoing, PI
- CCF-Tencent “Rhino Bird” Research Fund, **Efficient, Intelligent, and Adversary-Aware Attribution Analysis and Threat Hunting**, 2026/01-2026/12, Ongoing, PI
- CF-NSFOCUS “Kunpeng” Research Fund, **Large-Scale Attribution Analysis Based on Stream Processing in Cloud Computing Environments**, 2024/01-2024/12, Completed, PI
- Joint Fund of the National Natural Science Foundation of China, **Intelligent Detection and Attribution Methods and Key Technologies for APT Cyber Kill Chains**, 2021/01-2023/12, Completed, Core Technical Member


# 📝 Teaching
- Intelligent Software Quality Assurance (Autumn 2024, Autumn 2025)


# 🎓 Students
- **Undergraduate**: Chun Xu (UESTC)
- **2026**: Junjie Cheng, Yijie Xu
- **2025**: Shiyu Tan (1 * Patent, 1 * Competition Award), Yaokun Li, Qizhi Cai, Haocheng Li, Zhipeng Chen
- **2024**: Yuqiao Gu (Ph.D Student, 1 * Patent, 1 * Competition Award), Zhenkai Wang (TDSC Co-1st Author, ACNS 4th Author, Chinese Journal of Computers 3rd Author, 1 * Competition Award), Yi Jiang (Journal of Cybersecurity (Chinese) 1st Author, ACNS 3nd Author, 1 * Competition Award)
- **2023**: Jiahui Wang (APSEC'24 2nd Author, ICSE'26 5th Author, 1 * Patent), Mingxiang Shi (1 * Patent), Yangyang Wei (ICML'25 3rd Author, Chinese Journal of Computers 2nd Author, 3 * Patents, 1 * Competition Award), Yu Yang (ICSE'26 1st Author), Yao Zhu (ICML'25 1st Author)
- **Alumni**: None.


# 🎖 Honors and Awards
- *2025.12*, First Prize of Science and Technology Progress Award by China General Chamber of Commerce \(ranked 5/15\) 
- *2025.09*, Second Prize of Science and Technology Progress Award by Beijing Municipal  \(ranked 7/10\) 
- *2025.05*, National Second Prize and Outstanding Faculty Advisor Award in the Software Innovation Competition \(Software System Security Track\)
- *2025.03*, Research Contribution Award, School of Software Technology
- *2024.09*, Ningbo "YongJiang" Talent Programme (Youth Program)
- *2023.03*, Huawei's "Star of Tomorrow"
- *2021.02*, Zhejiang Lab's International Talent Fund for Young Professionals
- *2020.12*, Zhejiang University's Academic Rising Star 
- *2020.10*, China Scholarship Council (CSC) Joint Ph.D. Program (NUS)
- *2017.05*, Outstanding Graduate of Xidian University (Top 1%)
- *2015.11*, National Scholarship (Undergraduate) (Top 1%)


# 💬 Invited Talks
- *2020.10*, InForSec Cyber Security Academic Papers Sharing (Co-located with Beijing Cyber Security Conference)  \| [\[video\]](https://www.bilibili.com/video/BV1gy4y187Lq/?share_source=copy_web&vd_source=23dc4357b22105e2ec9569d56ca4163c)
- *2019.11*, Effective and Light-Weight Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts, CCS'19, London


# 🛎️ Academic Service
- **TPC Member**: IEEE GlobeCom CISS (2026, 2025)
- **Editorial Board Member**: Digital Twins and Applications(2025-2027)
- **Reviewer**: TIFS (2025), TDSC (2025, 2024), TBD (2025) EMSE (2025), TOSEM (2024), Computer & Security (2024), CAAI-TIT (2025), TII (2025), Chinese Journal of Computers (2025, 2024), Journal of Cybersecurity (Chinese) (2024), Computer Science (2024)
- **Subreviewer/External reviewer**: IEEE S&P (2025, 2024), NDSS (2026, 2022), AsiaCCS (2021), CCS (2019, 2018), ICDC (2019), ESORICS (2019)


# 📖 Educations
- *2017.09 - 2022.06*, Ph.D. in Cyber Security, Zhejiang University, Advised by [Prof. Yan Chen](https://users.cs.northwestern.edu/~ychen/).
- *2021.05 - 2022.04*, Visiting Ph.D. Student, National University of Singapore, Advised by [Prof. Zhenkai Liang](https://www.comp.nus.edu.sg/~liangzk/).
- *2015.09 - 2019.06*, B.S. in Information Security, Xidian University. 
- *2010.09 - 2013.06*, Zhenhai Middle School, Ningbo.


# 💻 Working Experience
- *2023.07 - now*, [School of Software Technology, Zhejiang University](https://www.zju.edu.cn), Ningbo/Hangzhou, China.
- *2022.07 - 2023.07*, [Huawei, 2012 Lab](https://www.huawei.com/en/), Hangzhou, China.

<a href="https://info.flagcounter.com/GT4T"><img src="https://s01.flagcounter.com/map/GT4T/size_s/txt_000000/border_CCCCCC/pageviews_1/viewers_0/flags_0/" alt="Flag Counter" border="0"></a>