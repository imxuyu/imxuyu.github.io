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

Hi! I am Yu Xu (徐榆), currently a Ph.D. student in Computer Application Technology at the University of Chinese Academy of Sciences (UCAS), co-advised by Prof. [Juan Cao]([https://github.com/](https://scholar.google.com/citations?user=fSBdNg0AAAAJ)), Prof. [Fan Tang](https://scholar.google.com/citations?user=PdKElfwAAAAJ). 
My research interests lie primarily in Visual Generation and Multimodal Large Language Models. I am passionate about advancing the frontiers of AI-driven content creation and multimodal understanding.
Currently, I am a Research Intern at **ByteDance**, focusing on foundational research for multimodal video generation. Prior to this, I was a Research Intern at **Tencent Hunyuan**, where I worked on unified image generation models. 

Before starting my Ph.D., I received my Master of Science in Computer Science from **The University of Hong Kong (HKU)**, supervised by Prof. [Benjamin Kao](https://scholar.google.com/citations?hl=en&user=TwSParMAAAAJ), where my research centered on Visual Question Answering. I also spent a wonderful time as a Research Assistant at **Kyoto University** in Japan, working on image enhancement algorithms under the guidance of Prof. [Masaaki Iiyama](https://scholar.google.com/citations?hl=en&user=MI-yYJYAAAAJ).

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Our paper [TAG-MoE](https://yuci-gpt.github.io/TAG-MoE/) has been accepted by CVPR 2026!
- *2026.01*: &nbsp;🎉🎉 Our paper [HeadRouter](https://yuci-gpt.github.io/headrouter/) has been accepted by ACM TOG 2026!
- *2025.08*: &nbsp;🎉🎉 Our paper [In-Context Brush](https://yuci-gpt.github.io/In-Context-Brush/) has been accepted by SIGGRAPH ASIA 2025!
- *2025.03*: &nbsp;🎉🎉 Our paper [B4M](https://yuci-gpt.github.io/B4M//) has been accepted by ACM TOG 2025!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/TAG-MoE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TAG-MoE: Task-Aware Gating for Unified Generative Mixture-of-Experts](https://yuci-gpt.github.io/TAG-MoE/)

**Yu Xu**, Hongbin Yan, Juan Cao, Yiji Cheng, Tiankai Hang, Runze He, Zijin Yin, Shiyi Zhang, Yuxin Zhang, Jintao Li, Chunyu Wang, Qinglin Lu, Tong-Yee Lee, Fan Tang

<p><b><u>TL;DR:</u></b> Standard MoE routers are task-agnostic and struggle with conflicting generative objectives. TAG-MoE introduces <strong>Predictive Alignment Regularization</strong> to explicitly align internal routing decisions with high-level task semantics, transforming the MoE gate into an intelligent, <strong>task-aware dispatch center</strong> for unified image synthesis.</p>

[**Project**](https://yuci-gpt.github.io/TAG-MoE/) <strong><span class='show_paper_citations'

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Headrouter: A training-free image editing framework for mm-dits by adaptively routing attention heads](https://yuci-gpt.github.io/HeadRouter/)

**Yu Xu**, Fan Tang, Juan Cao, Xiaoyu Kong, Yuxin Zhang, Jintao Li, Oliver Deussen, Tong-Yee Lee

<p><b><u>TL;DR:</u></b> Standard MoE routers are task-agnostic and struggle with conflicting generative objectives. TAG-MoE introduces <strong>Predictive Alignment Regularization</strong> to explicitly align internal routing decisions with high-level task semantics, transforming the MoE gate into an intelligent, <strong>task-aware dispatch center</strong> for unified image synthesis.</p>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM TOG 2026</div><img src='images/HeadRouter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Headrouter: A training-free image editing framework for mm-dits by adaptively routing attention heads](https://yuci-gpt.github.io/HeadRouter/)

**Yu Xu**, Fan Tang, Juan Cao, Xiaoyu Kong, Yuxin Zhang, Jintao Li, Oliver Deussen, Tong-Yee Lee

<p><b><u>TL;DR:</u></b> This work investigates the semantic sensitivity of attention heads in MM-DiTs  and introduces a <strong>training-free</strong> framework that adaptively routes and reinforces these heads for instance-specific image editing.</p>


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
