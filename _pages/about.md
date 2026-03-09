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

I am Yu Xu (徐榆), currently a Ph.D. student in Computer Application Technology at the **University of Chinese Academy of Sciences**, supervised by Prof. [Juan Cao](https://scholar.google.com/citations?user=fSBdNg0AAAAJ) and Dr. [Fan Tang](https://scholar.google.com/citations?user=PdKElfwAAAAJ). 

Currently, I am a Research Intern at **ByteDance**, working on unified multimodal video generation research. Prior to this, I was a Research Intern at **Tencent Hunyuan**, where I worked on unified image generation models research. 

Before starting my Ph.D., I received my Master of Science in Computer Science from **The University of Hong Kong**, supervised by Prof. [Benjamin Kao](https://scholar.google.com/citations?hl=en&user=TwSParMAAAAJ), where my research focus on Visual Question Answering. I also spent a wonderful time as a Research Assistant at **Kyoto University** in Japan, working on image enhancement algorithms supervised by Prof. [Masaaki Iiyama](https://scholar.google.com/citations?hl=en&user=MI-yYJYAAAAJ) and Dr. [Atsushi Hashimoto](https://scholar.google.com/citations?user=DHIGVL8AAAAJ).

My research interests lie primarily in Visual Generation and Multimodal Large Language Models. I am passionate about advancing the frontiers of Artificial Intelligence Generated Content (AIGC) and multimodal understanding.

# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Our paper [TAG-MoE](https://yuci-gpt.github.io/TAG-MoE/) has been accepted by CVPR 2026!
- *2026.02*: &nbsp;🎉🎉 Our paper [Re-align](https://arxiv.org/abs/2601.05124) has been accepted by CVPR 2026!
- *2026.02*: &nbsp;🎉🎉 Our paper Meta-CoT has been accepted by CVPR 2026!
- *2026.01*: &nbsp;🎉🎉 Our paper [HeadRouter](https://yuci-gpt.github.io/headrouter/) has been accepted by ACM TOG 2026!
- *2025.08*: &nbsp;🎉🎉 Our paper [In-Context Brush](https://yuci-gpt.github.io/In-Context-Brush/) has been accepted by SIGGRAPH ASIA 2025!
- *2025.03*: &nbsp;🎉🎉 Our paper [B4M](https://yuci-gpt.github.io/B4M/) has been accepted by ACM TOG 2025!

# 📝 Selected Publications 
<!-- paper x -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/TAG-MoE.png' loading="lazy" alt="TAG-MoE"></div></div>
<div class='paper-box-text' markdown="1">
[TAG-MoE: Task-Aware Gating for Unified Generative Mixture-of-Experts](https://yuci-gpt.github.io/TAG-MoE/)

**Yu Xu**, Hongbin Yan, Juan Cao, Yiji Cheng, Tiankai Hang, Runze He, Zijin Yin, Shiyi Zhang, Yuxin Zhang, Jintao Li, Chunyu Wang, Qinglin Lu, Tong-Yee Lee, Fan Tang

<b><u>TL;DR:</u></b> Standard MoE routers are task-agnostic and struggle with conflicting generative objectives. TAG-MoE introduces <strong>Predictive Alignment Regularization</strong> to explicitly align internal routing decisions with high-level task semantics, transforming the MoE gate into an intelligent, <strong>task-aware dispatch center</strong> for unified image synthesis.

<p class="conf-color">IEEE Conference on Computer Vision and Pattern Recognition (CVPR'26)</p>

[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-TAGMoE-orange.svg)](https://yuci-gpt.github.io/TAG-MoE/) [![arxiv](https://img.shields.io/badge/ArXiv-2601.08881-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2601.08881) [![hf-paper](https://img.shields.io/badge/HF%20Paper-Daily-ffcc00.svg?logo=huggingface)](https://huggingface.co/papers/2601.08881) [![code](https://img.shields.io/github/stars/ICTMCG/TAG-MoE?style=social&label=Code+Stars)](https://github.com/ICTMCG/TAG-MoE)

</div>
</div>


<!-- paper x -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">TOG 2026</div><img src='images/HeadRouter.png' loading="lazy" alt="HeadRouter"></div></div>
<div class='paper-box-text' markdown="1">
[Headrouter: A training-free image editing framework for mm-dits by adaptively routing attention heads](https://yuci-gpt.github.io/HeadRouter/)

**Yu Xu**, Fan Tang, Juan Cao, Xiaoyu Kong, Yuxin Zhang, Jintao Li, Oliver Deussen, Tong-Yee Lee

<b><u>TL;DR:</u></b> HeadRouter investigates the semantic sensitivity of attention heads in MM-DiTs  and introduces a <strong>training-free</strong> framework that adaptively routes and reinforces these heads for instance-specific image editing.

<p class="conf-color">ACM Transactions on Graphics (TOG'26)</p>

[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-HeadRouter-orange.svg)](https://yuci-gpt.github.io/HeadRouter/) [![arxiv](https://img.shields.io/badge/ArXiv-2601.08881-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2411.15034) [![hf-paper](https://img.shields.io/badge/HF%20Paper-Daily-ffcc00.svg?logo=huggingface)](https://huggingface.co/papers/2411.15034) [![code](https://img.shields.io/github/stars/ICTMCG/HeadRouter?style=social&label=Code+Stars)](https://github.com/ICTMCG/HeadRouter)

</div>
</div>


<!-- paper x -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">SIGGRAPH ASIA 2025</div><img src='images/In-Context-Brush.png' loading="lazy" alt="In-Context-Brush"></div></div>
<div class='paper-box-text' markdown="1">
[In-Context Brush: Zero-shot Customized Subject Insertion with Context-Aware Latent Space Manipulation](https://yuci-gpt.github.io/In-Context-Brush/)

**Yu Xu**, Fan Tang, You Wu, Lin Gao, Oliver Deussen, Hongbin Yan, Jintao Li, Juan Cao, Tong-Yee Lee

<b><u>TL;DR:</u></b> In-Context Brush is a zero-shot customized subject insertion framework that reformulates the task as In-Context Learning (ICL) in MM-DiTs, utilizing latent feature shifting and head-wise reweighting to achieve high-fidelity, text-controllable subject injection without any model tuning.

<p class="conf-color">ACM Special Interest Group on Computer Graphics and Interactive Techniques in Asia (SIGGRAPH ASIA'26)</p>

[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-InContextBrush-orange.svg)](https://yuci-gpt.github.io/In-Context-Brush/) [![arxiv](https://img.shields.io/badge/ArXiv-2505.20271-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2505.20271) [![hf-paper](https://img.shields.io/badge/HF%20Paper-Daily-ffcc00.svg?logo=huggingface)](https://huggingface.co/papers/2505.20271) [![code](https://img.shields.io/github/stars/ICTMCG/In-context-Brush?style=social&label=Code+Stars)](https://github.com/ICTMCG/In-context-Brush) [![youtube](https://img.shields.io/badge/YouTube-Video-FF0000.svg?logo=youtube&logoColor=white)](https://youtu.be/qtQH4IbiyH8)[![wechat](https://img.shields.io/badge/WeChat-Blog-07C160.svg?logo=wechat&logoColor=white)](https://mp.weixin.qq.com/s/6-V-FQ2zavFnpkGgIND57Q)

</div>
</div>


<!-- paper x -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">TOG 2025</div><img src='images/B4M.png' loading="lazy" alt="B4M"></div></div>
<div class='paper-box-text' markdown="1">
[B4M: Breaking Low-Rank Adapter for Making Content-Style Customization](https://dl.acm.org/doi/full/10.1145/3728461)

**Yu Xu**, F Tang, J Cao, Y Zhang, O Deussen, W Dong, J Li, TY Lee

<b><u>TL;DR:</u></b> B4M introduces a novel "break-for-make" pipeline that disentangles content and style customization by separating LoRA into distinct sub-parameter spaces via <strong>Partly Learnable Projection (PLP)</strong>, and harmoniously fuses them using <strong>Riemannian Preconditioning</strong>.

<p class="conf-color">ACM Transactions on Graphics (TOG'25)</p>

[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-B4M-orange.svg)](https://yuci-gpt.github.io/B4M/) [![arxiv](https://img.shields.io/badge/ArXiv-2403.19456-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2403.19456) [![hf-paper](https://img.shields.io/badge/HF%20Paper-Daily-ffcc00.svg?logo=huggingface)](https://huggingface.co/papers/2403.19456) [![code](https://img.shields.io/github/stars/ICTMCG/Break-for-make?style=social&label=Code+Stars)](https://github.com/ICTMCG/Break-for-make)[![wechat](https://img.shields.io/badge/WeChat-Blog-07C160.svg?logo=wechat&logoColor=white)](https://mp.weixin.qq.com/s/gXG7jp4PvGE_YcNO0sQKrw)

</div>
</div>



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
