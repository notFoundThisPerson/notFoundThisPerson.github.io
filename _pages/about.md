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

# 💼 About Me

Graduated from State Key Laboratory of Multimodal Artificial Intelligence Systems, Institute of Automation, Chinese Academy of Sciences, I have been studying robotics and embodied AI since my school time. With the aim of creating agents that can actually serve people in daily life, my research focuses on enhancing MLLM capabilities in tool use and task completion through SFT, RL, and benchmark construction, particularly in **‌GUI Agents**‌ and **‌Embodied AI**‌. Multiple research publications have been authored in the fields of GUI Agents, VLA models and benchmarks with total <a href='https://scholar.google.com/citations?user=7Z55xewAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> on [Google Scholar](https://scholar.google.com/citations?user=7Z55xewAAAAJ&hl=zh-CN). The academic supervisor during my master's degree was Prof. [Yinghao Cai](https://people.ucas.ac.cn/~yhcai).

# 🔥 News
- *2025.10*: &nbsp;🎉🎉 Our new MLLM **LongCat-Flash-Omni** has been open sourced!
- *2025.06*: &nbsp;🎉🎉 Two papers have been accepted by ICCV 2025!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='images/longcat.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">
[LongCat-Flash-Omni Technical Report](https://arxiv.org/pdf/2511.00279)

Meituan LongCat Team

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=7Z55xewAAAAJ&citation_for_view=7Z55xewAAAAJ:TFP_iSt0sucC) <strong><span class='show_paper_citations' data='7Z55xewAAAAJ:TFP_iSt0sucC'></span></strong>
- A state-of-the-art open-source omni-modal model with 560 billion parameters, excelling at real-time audio-visual interaction.
- Adopts a curriculum-inspired progressive training strategy to achieve comprehensive multimodal capabilities while maintaining strong unimodal capability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='images/uitron.png' lt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">
[UItron: Foundational GUI Agent with Advanced Perception and Planning](https://arxiv.org/pdf/2508.21767)

Zhixiong Zeng, Jing Huang, **Liming Zheng**, Wenkang Han, Yufeng Zhong, Lei Chen, Longrong Yang, Yingjie Chu, Yuzhi He, Lin Ma

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=7Z55xewAAAAJ&citation_for_view=7Z55xewAAAAJ:hC7cP41nSMkC) <strong><span class='show_paper_citations' data='7Z55xewAAAAJ:hC7cP41nSMkC'></span></strong>
- A foundational model for automatic GUI agents, which advances GUI agent development via systematic data engineering, an interactive environment, and a curriculum reinforcement learning framework, achieving superior performance in GUI tasks and interaction with top-tier Chinese mobile APPs.
</div>
</div>

- [GPDAN: Grasp Pose Domain Adaptation Network for Sim-to-real 6-DoF Object Grasping](https://ieeexplore.ieee.org/abstract/document/10153686), **Liming Zheng**, Wenxuan Ma, Yinghao Cai, Tao Lu, Shuo Wang. **RA-L 2023**

- [RoboTron-Mani: All-in-One Multimodal Large Model for Robotic Manipulation](https://openaccess.thecvf.com/content/ICCV2025/papers/Yan_RoboTron-Mani_All-in-One_Multimodal_Large_Model_for_Robotic_Manipulation_ICCV_2025_paper.pdf), Feng Yan, Fanfan Liu, Yiyang Huang, Zechao Guan, **Liming Zheng**, Yufeng Zhong, Chengjian Feng, Lin Ma. **ICCV 2025**

- [DataPlatter: Boosting Robotic Manipulation Generalization with Minimal Costly Data](https://arxiv.org/pdf/2503.19516), **Liming Zheng**, Feng Yan, Fanfan Liu, Chengjian Feng, Yufeng Zhong, Yiyang Huang, Lin Ma. ArXiv preprint

- [RoboCAS: A Benchmark for Robotic Manipulation in Complex Object Arrangement Scenarios](https://arxiv.org/pdf/2407.06951), **Liming Zheng**, Feng Yan, Fanfan Liu, Chengjian Feng, Zhuoliang Kang, Lin Ma. ArXiv preprint

- [VGPN: 6-DoF grasp pose detection network based on hough voting](https://ieeexplore.ieee.org/abstract/document/9981925), **Liming Zheng**, Yinghao Cai, Tao Lu, Shuo Wang. **IROS 2022**

- [More](https://scholar.google.com/citations?user=7Z55xewAAAAJ&hl=zh-CN)

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2023.03* First prize of 2023 Intel Grand Challenge on Indoor Robot Learning, as team lead of Baymax.

# 📖 Educations
- *2020.09 - 2023.06*, Master of Electronic and Information Engineering, Institute of Automation, Chinese Academy of Sciences, Beijing, China.
- *2016.09 - 2020.06*, Undergraduate Student, Nanjing University of Science and Technology, Nanjing, China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Work Experience
- *2023.07 - Now*, AI Reasher, [Meituan](https://www.meituan.com/), Beijing, China.