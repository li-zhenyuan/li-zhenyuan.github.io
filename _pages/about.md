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

My research interests lie in **system security**, **intrusion detection**, and **cyber threat analysis**. My current work focuses on designing practical intrusion detection and attack investigation systems. I work closely with my PhD advisors, Prof. [Yan Chen](https://users.cs.northwestern.edu/~ychen/) from Northwestern University and Prof. [Shouling Ji](https://nesa.zju.edu.cn) from Zhejiang University.

<!-- **Research Map:**

<img src='images/李振源-2025年ACES暑期工作会议_05.png' alt="sym" width="86%"> -->

**Recent research interests include:**
- Intelligent yet Effcient Cyber Attack Hunting.
- Action Security for LLM Agents.
- LLM-powered Security Analysis.

Feel free to [contact me](mailto:li_zhenyuan@qq.com) if you are interested in industry-oriented security research.（**招收2026级硕士生4-5名，欢迎联系！**）


# 🔥 News
- 🏗️ *2025.07*: Granted CCF-Tencent "Bucerotidae" Open Fund as PI.
- 📑 *2025.07*: 我们的论文“智能溯源分析与入侵检测：洞察、挑战与展望”被《计算机学报》接收。
- 📑 *2025.07*: Our paper "AutoSeg: Automatic Micro-segmentation Policy Generation via Configuration Analysis" is accepted by Computer & Security.
- 🎉 *2025.05*：指导作品“重明鸟：海量日志流中高隐蔽威胁在线检测系统”获软件创新大赛-软件系统安全赛“全国二等奖”及“优秀指导教师奖”，恭喜参与同学。 \[[Link](http://www.ccsssc.com/notice)\]
- 📑 *2025.05*: Our paper "The Case for Learned Provenance-based System Behavior Baseline" is accepted by ICML'25.
- 📑 *2025.04*: One paper "PentestAgent: Incorporating LLM Agents to Automated Penetration Testing" is accepted by AsiaCCS'25.
- 📃 *2025.02*: One poster “[LLM-Driven Automated Exploit Assessment for Penetration Testing](https://ndss25-posters.hotcrp.com/u/0/doc/ndss25-posters-final71.pdf)” will appear in NDSS'25 poster session.
- 🏗️ *2024.12*: Granted "Leading Goose" R&D Program of Zhejiang as PI.
- 📑 *2024.12*: One paper "Understanding the Business of Online Affiliate Marketing: An Empirical Study" is accepted by INFOCOM'25.
- 🎉 *2024.09*: Awarded Ningbo "YongJiang" Talent Programme (Youth Program).
- 🏗️ *2024.08*: Granted National Natural Science Foundation of China (Youth Program) as PI.
- 📑 *2024.08*: Our paper "Incorporating Gradients to Rules: Towards Lightweight, Adaptive Provenance-based Intrusion Detection" is accepted by NDSS'25.
- 📑 *2024.01*: One paper "Decoding the MITRE Engenuity ATT&CK Enterprise Evaluation: An Analysis of EDR Performance in Real-World Environments" is accepted by AsiaCCS'24.


# 🛠️ Projects
- [Aurora: Automated Cyberattack Emulation](https://github.com/LexusWang/Aurora-demos?tab=readme-ov-file)
- [Marlin: Streaming Provenance Graph Analysis](https://github.com/MarineYY/MARLIN)


# 📝 Selected Publications 

**Full List: [Google Scholar](https://scholar.google.com/citations?user=3YGMOdwAAAAJ)** 
(* Equally Contribution, # Corresponding Author)

- ``计算机学报`` “智能溯源分析与入侵检测：洞察、挑战与展望” **李振源**，韦洋洋，王征凯，纪守领 

- ``COSE 2025`` "AutoSeg: Automatic Micro-segmentation Policy Generation via Configuration Analysis", Andong Chen, Zhaoxuan Jin, **Zhenyuan Li#**, Yan Chen, Yu Ning, Ying Wang 

- ``ICML 2025`` "The Case for Learned Provenance-based System Behavior Baseline", Yao Zhu\*, **Zhenyuan LI\*#**, Yangyang Wei, Shouling Ji 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/aurora.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[From Sands to Mansions: Towards Automated Cyberattack Emulation with Classical Planning and Large Language Models](https://arxiv.org/pdf/2407.16928)"

Lingzhi Wang, **Zhenyuan Li**, Yi Jiang, Zhengkai Wang, Zonghan Guo, Jiahui Wang, Yangyang Wei, Xiangmin Shen, Ruan Wei, Yan Chen

[**Project**](https://github.com/LexusWang/Aurora-demos?tab=readme-ov-file) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:UeHWp8X0CEIC'></span></strong> 
![](https://img.shields.io/github/stars/LexusWang/Aurora-demos?style=social)

- AURORA leverages a modular attack model and LLM to automatically generate and execute complex cyberattacks, aiming to create a large-scale, realistic dataset for enhancing cyber defense. By automating attack planning, environment setup, and semi-automatic execution, AURORA successfully constructed a dataset of over 1,000 attack chains.

</div>
</div>

- ``AsiaCCS 2025`` "PentestAgent: Incorporating LLM Agents to Automated Penetration Testing", Xiangmin Shen, Lingzhi Wang, **Zhenyuan Li**, Yan Chen, Wencheng Zhao, Dawei Sun, Jiashui Wang, Wei Ruan

- ``INFOCOM 2025`` "Understanding the Business of Online Affiliate Marketing: An Empirical Study", Haitao Xu, Yiwen Sun, Kaleem Ullah Qasim, Shuai Hao, Wenrui Ma, **Zhenyuan Li**, Fan Zhang, Meng Han, Zhao Li

- ``NDSS 2025`` "[Incorporating Gradients to Rules: Towards Lightweight, Adaptive Provenance-based Intrusion Detection](https://arxiv.org/pdf/2404.14720)", Lingzhi Wang, Xiangmin Shen, Weijian Li, **Zhenyuan Li#**, R Sekar, Han Liu, Yan Chen
  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2024</div><img src='images/Marlin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[Marlin: Knowledge-Driven Analysis of Provenance Graphs forEfficient and Robust Detection of Cyber Attacks](https://arxiv.org/pdf/2403.12541)"

**Zhenyuan Li**, Yangyang Wei, Xiangmin Shen, Lingzhi Wang, Yan Chen, Haitao Xu, Shouling Ji, Fan Zhang, Liang Hou, Wenmao Liu, Xuhong Zhang, Jianwei Ying

[**Project**](https://github.com/MarineYY/MARLIN) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:UeHWp8X0CEIC'></span></strong> 
![](https://img.shields.io/github/stars/MarineYY/MARLIN?style=social)

- Marlin conceptualize real-time attack detection in streaming logs as a streaming graph alignment problem, leveraging query graphs to pinpoint critical elements in the provenance graph. Integrated into a tag propagation framework, it processes each event once, reducing redundancy and enhancing efficiency and defense against evasion.
    
</div>
</div>

- ``AsiaCCS 2024`` "[Decoding the MITRE Engenuity ATT&CK Enterprise Evaluation: An Analysis of EDR Performance in Real-World Environments](https://dl.acm.org/doi/pdf/10.1145/3634737.3645012)", Xiangmin Shen, **Zhenyuan Li**, Graham Burleigh, Lingzhi Wang, Yan Chen

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESORICS 2022</div><img src='images/AttacKG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[AttacKG: Constructing Technique Knowledge Graph from Cyber Threat Intelligence Reports](https://link.springer.com/chapter/10.1007/978-3-031-17140-6_29)"

**Zhenyuan Li**, Jun Zeng, Yan Chen, Zhenkai Liang

[**Project**](https://github.com/li-zhenyuan/Knowledge-enhanced-Attack-Graph) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:UeHWp8X0CEIC'></span></strong> 
![](https://img.shields.io/github/stars/li-zhenyuan/Knowledge-enhanced-Attack-Graph?style=social)

- AttacKG can automatically extract structured attack behavior graphs from CTI reports and identify the associated attack techniques, and aggregate threat intelligence across reports to collect different aspects of techniques and enhance attack behavior graphs into technique knowledge graphs (TKGs).
- AttacKG can empower many downstream security applications such as **threat identification**, **automatic threat reasoning and disposition**.
</div>
</div>

- ``TDSC 2022`` "[RATScope: Recording and Reconstructing Missing RAT Semantic Behaviors for Forensic Analysis on Windows](https://ieeexplore.ieee.org/document/9234076)", Runqing Yang, Xutong Chen, Haitao Xu, Yueqiang Chen, Chunlin Xiong, Linqi Ruan, Mohammad Kavousl, **Zhenyuan Li**, Liheng Xu, Yan Chen 

- ``COSE 2021`` "[Threat Detection and Investigation with System-level Provenance Graphs: A Survey](https://www.sciencedirect.com/science/article/pii/S0167404821001061)", **Zhenyuan Li**, Qi Alfred Chen, Yang Runqing, Yan Chen

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2019</div><img src='images/CCS19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

"[Effective and Light-Weight Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts](https://dl.acm.org/doi/10.1145/3319535.3363187)"

**Zhenyuan Li**, Qi Alfred Chen, Chunlin Xiong, Yan Chen, Tiantian Zhu, Hai Yang

[**Project**](https://github.com/li-zhenyuan/Effective-and-Light-Weight-Deobfuscation-and-Semantic-Aware-Attack-Detection-for-PowerShell-Scripts) <strong><span class='show_paper_citations' data='3YGMOdwAAAAJ:u-x6o8ySG0sC'></span></strong>
![](https://img.shields.io/github/stars/li-zhenyuan/Effective-and-Light-Weight-Deobfuscation-and-Semantic-Aware-Attack-Detection-for-PowerShell-Scripts?style=social)

- The first effective and light-weight deobfuscation approach for PowerShell scripts. Adopted in the product of an [startup security company](https://www.fyreshld.com/) <img src='./images/MingYan.jpg' style='width: 4em;'>.
</div>
</div>


# 📑 Selected Patents
- **全量数据采集**：“（受理）基于 eBPF 的 Android 系统细粒度溯源数据采集方法及装置”、“（授权）基于多层数据融合的云平台细粒度溯源数据采集方法与系统”
- **高效威胁狩猎**：“（授权）基于标签传递和事件基线学习的实时攻击链检测方法及系统”、“（授权）基于标签和图对齐的流式溯源图实时攻击检测方法及系统”、“（受理）基于大模型的可疑点前后向追踪与攻击路径还原方法及系统”、“（受理）基于大模型多智能体决策树的应用风险判定方法及装置”
- **智能规则优化**：“（授权）基于迭代预测校正的流式溯源图的异常检测方法及系统”、“（授权）基于特征反向传播的攻击检测策略优化方法及系统”
- **自动攻击规划**：“（受理）一种端到端网络攻击构建方法”、“（受理）基于大语言模型和攻击树模型的多阶段自动化渗透测试方案生成方法及系统”



# 💫 Selected Fundings
- CCF-腾讯“犀牛鸟”科研基金，**高效、智能、对抗导向的溯源分析与威胁狩猎方法与关键技术研究**，2026/01-2026/12，获批，项目负责人
- 国家自然基金青年科学基金项目，**云原生下大规模实时溯源分析与攻击检测方法和关键技术研究**，2025/01-2027/12，在研，项目负责人
- 浙江省“领雁”研发计划，**面向某平台的攻击规划与编排**，2025/01-2025/12，在研，项目负责人
- 宁波市“甬江”青年人才项目，**关键基础设施云平台安全防护关键技术研究**，2025/01-2027/12，在研，项目负责人
- 国家重点研发计划“网络空间安全治理”专项，**面向终端的高隐蔽传播网络公害识别，取证和归因研究**，2024/01-2026/12，在研，子课题负责人
- CCF-绿盟“鲲鹏”科研基金，**云计算环境下基于流处理的大规模溯源分析**，2024/01-2024/12，结题，项目负责人
- 国家自然科学基金联合基金项目，**面向APT网络攻击链的智能检测与溯源方法及关键技术研究**，2021/01-2023/12，结题，技术骨干


# 📝 Teaching
- 智能软件质量保障（2024年秋，2025年秋）


# 🎓 Students
- **2025**: 
  - Shiyu Tan (1 * Patent, 1 * Competition Award)
  - Yaokun Li, Qizhi Cai, Haocheng Li, Zhipeng Chen
- **2024**: 
  - Yuqiao Gu (Ph.D Student, 1 * Patent, 1 * Competition Award)
  - Zhenkai Wang (计算机学报三作, 1 * Competition Award)
  - Yi Jiang (1 * Competition Award)
- **2023**: 
  - Jiahui Wang (APSEC'24 2nd Author, 1 * Patent)
  - Mingxiang Shi (1 * Patent)
  - Yangyang Wei (计算机学报二作, ICML'25 3rd Author, 3 * Patents, 1 * Competition Award)
  - Yu Yang (ICSE'26 in submission 1st Author)
  - Yao Zhu (ICML'25 1st Author)
- **Alumni**: None.


# 🎖 Honors and Awards
- *2025-05* 软件系统安全赛“全国二等奖”及“优秀指导教师奖”
- *2025-03* 浙江大学软件学院“科研贡献奖”
- *2024-09* Ningbo "YongJiang" Talent Programme (Youth Program).
- *2021-02* Zhejiang Lab's International Talent Fund for Young Professionals
- *2020-12* Zhejiang University's Academic Rising Star 
- *2020-10* CSC Joint Ph.D. Program
- *2017-05* Outstanding Graduate of Xidian University (Top 1%)
- *2015-11* National Scholarship (Undergraduate) (Top 1%)


# 💬 Invited Talks
- *2020.10*, InForSec Cyber Security Academic Papers Sharing (Co-located with Beijing Cyber Security Conference)  \| [\[video\]](https://www.bilibili.com/video/BV1gy4y187Lq/?share_source=copy_web&vd_source=23dc4357b22105e2ec9569d56ca4163c)
- *2019.11*, Effective and Light-Weight Deobfuscation and Semantic-Aware Attack Detection for PowerShell Scripts, CCS'19, London


# 🛎️ Academic Service
- **Reviewer**: TIFS(2025), TDSC(2025, 2024), EMSE(2025), TOSEM (2024), Computer & Security(2024), 计算机学报 (2025, 2024), 信息安全学报 (2024), 计算机科学 (2024), IEEE Access (2020)
- **TPC Member**: IEEE Globecom 2025 CISS
- **Subreviewer/External reviewer**: IEEE S&P (2025, 2024), NDSS (2022), AsiaCCS (2021), CCS (2019, 2018), ICDC (2019), ESORICS (2019)


# 📖 Educations
- *2017.09 - 2022.06*, Ph.D. in Cyber Security, Zhejiang University, Advised by [Prof. Yan Chen](https://users.cs.northwestern.edu/~ychen/).
- *2021.05 - 2022.04*, Visiting Ph.D. Student, National University of Singapore, Advised by [Prof. Zhenkai Liang](https://www.comp.nus.edu.sg/~liangzk/).
- *2015.09 - 2019.06*, B.S. in Information Security, Xidian University. 
- *2010.09 - 2013.06*, Zhenhai Middle School, Ningbo.


# 💻 Working Experience
- *2023.07 - now*, [Zhejiang University](https://www.zju.edu.cn), Hangzhou, China.
- *2022.07 - 2023.07*, [Huawei, 2012 Lab](https://www.huawei.com/en/), Hangzhou, China.

<a href="https://info.flagcounter.com/GT4T"><img src="https://s01.flagcounter.com/map/GT4T/size_s/txt_000000/border_CCCCCC/pageviews_1/viewers_0/flags_0/" alt="Flag Counter" border="0"></a>