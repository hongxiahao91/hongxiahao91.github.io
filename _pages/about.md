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
# About me
I am currently a second-year master student (2022 - present) at [Department of Computer Science and Engineering](https://www.cs.sjtu.edu.cn/) at [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), under the supervision of [Prof. Rui Wang](https://wangruinlp.github.io/). Before that, I received my bachelor degree in Computer Science and Engineering from Shanghai Jiao Tong University (SJTU) in 2022.

I interned at [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/) (2023 with Dr. [Shujie Liu](https://www.microsoft.com/en-us/research/people/shujliu/?from=https://research.microsoft.com/en-us/people/shujliu/&type=exact) and [Long Zhou](https://long-zhou.github.io/)) and [Tencent AI Lab](https://ai.tencent.com/ailab/en/index) (2021-2023 with Dr. [Lemao Liu](https://lemaoliu.github.io/homepage/)). Now I am a machine learning engineer intern at [ByteDance](https://www.bytedance.com/en/), working on multimodal large language models.


# 🔬 Research Interest

**Large Language Model**: Multimodal Large Language Models, Speech Large Language Model, Video Understanding Large Language Model, etc.

**Natural Language Processing**: Neural Machine Translation, Open-Ended Text Generation, etc.


# 🔥 News
- *2024.03*: 🎉🎉 One paper about evaluating large language models (CLEAN-EVAL) is accepted by [NAACL 2024 Findings](https://2024.naacl.org/).
- *2024.03*: 🎉🎉 Q-Refine is accepted by [ICME 2024](https://2024.ieeeicme.org/).
- *2023.01*: I join ByteDance as a machine learning engineer intern.
- *2023.10*: 🎉🎉 Penalty Decoding is accepted by [EMNLP 2023](https://2023.emnlp.org/).
- *2023.05*: 🎉🎉 One paper about translation memory augmented NMT is accepted by [ACL 2023 Findings](https://2023.aclweb.org/).
- *2023.04*: I join Microsoft Research Asia (MSRA), Natural Language Computing group as a research intern.
- *2022.06*: I graduate from Shanghai Jiao Tong University and receive the Bachelor of Engineering in Computer Science and Engineering (with honor of Shanghai Jiao Tong University Outstanding Graduates).
- *2021.12*: I join Tencent AI Lab, Natural Language Processing center as a research intern.



# 📝 Publications 
\* denotes co-first authors
- [Rethinking Translation Memory Augmented Neural Machine Translation](https://aclanthology.org/2023.findings-acl.162/)

  **Hongkun Hao**, Guoping Huang, Lemao Liu, Zhirui Zhang, Shuming Shi, Rui Wang

  ``ACL 2023 Findings`` \| <a href='https://github.com/hongkunhao/translation_memory_augmented_NMT'><button class="code-btn">CODE</button></a> <button class="copy-btn" data-bib-file="hao-etal-2023-rethinking">BIB</button>


- [Penalty Decoding: Well Suppress the Self-Reinforcement Effect in Open-Ended Text Generation](https://aclanthology.org/2023.emnlp-main.78/) 

  Wenhong Zhu, **Hongkun Hao**, Rui Wang

  ``EMNLP 2023`` \| <a href='https://github.com/hongkunhao/penalty_decoding'><button class="code-btn">CODE</button></a> <button class="copy-btn" data-bib-file="zhu-etal-2023-penalty">BIB</button>


- [Q-Refine: A Perceptual Quality Refiner for AI-Generated Image](https://arxiv.org/abs/2401.01117.pdf)
  
  Chunyi Li, Haoning Wu, Zicheng Zhang, **Hongkun Hao**, Kaiwei Zhang, Lei Bai, Xiaohong Liu, Xiongkuo Min, Weisi Lin, Guangtao Zhai
  
  ``ICME 2024`` \| <a href='https://github.com/Q-Future/Q-Refine'><button class="code-btn">CODE</button></a> <button class="copy-btn" data-bib-file="li2024qrefine">BIB</button>


- [CLEAN-EVAL: Clean Evaluation on Contaminated Large Language Models](https://arxiv.org/abs/2311.09154)
  
  Wenhong Zhu, **Hongkun Hao**, Zhiwei He, Yunze Song, Yumeng Zhang, Hanxu Hu, Yiran Wei, Rui Wang, Hongyuan Lu
  
  ``NAACL 2024 Findings`` \| <a href='https://github.com/hongkunhao'><button class="code-btn">CODE</button></a> <button class="copy-btn" data-bib-file="zhu2024cleaneval">BIB</button>



<span class='anchor' id='preprints'></span>
# 🖨️ Preprints
\* denotes co-first authors
- [Boosting Large Language Model for Speech Synthesis: An Empirical Study](https://arxiv.org/abs/2401.00246.pdf)
  
  **Hongkun Hao**, Long Zhou, Shujie Liu, Jinyu Li, Shujie Hu, Rui Wang, Furu Wei

  <button class="copy-btn" data-bib-file="hao2023boosting">BIB</button>


- [Improving Open-Ended Text Generation via Adaptive Decoding](https://arxiv.org/abs/2402.18223)
  
  Wenhong Zhu, **Hongkun Hao**, Zhiwei He, Yiming Ai, Rui Wang

  <a href='https://github.com/hongkunhao/adaptive_decoding'><button class="code-btn">CODE</button></a> <button class="copy-btn" data-bib-file="zhu2024improving">BIB</button>


- [Can Watermarks Survive Translation? On the Cross-lingual Consistency of Text Watermark for Large Language Models](https://arxiv.org/abs/2402.14007)

  Zhiwei He\*, Binglin Zhou\*, **Hongkun Hao**, Aiwei Liu, Xing Wang, Zhaopeng Tu, Zhuosheng Zhang, Rui Wang

  <a href='https://github.com/zwhe99/X-SIR'><button class="code-btn">CODE</button></a> <button class="copy-btn" data-bib-file="he2024can">BIB</button> <a href='https://cross-lingual-watermark.github.io/'><button class="home-btn">HOME</button></a>


- [Is Cognition and Action Consistent or Not: Investigating Large Language Model's Personality](https://arxiv.org/abs/2402.14679)

  Yiming Ai, Zhiwei He, Ziyin Zhang, Wenhong Zhu, **Hongkun Hao**, Kai Yu, Lingjun Chen, Rui Wang

  <button class="copy-btn" data-bib-file="ai2024cognition">BIB</button>


- [WavLLM: Towards Robust and Adaptive Speech Large Language Model](https://arxiv.org/abs/2404.00656)

  Shujie Hu, Long Zhou, Shujie Liu, Sanyuan Chen, **Hongkun Hao**, Jing Pan, Xunying Liu, Jinyu Li, Sunit Sivasankaran, Linquan Liu, Furu Wei

  <button class="copy-btn" data-bib-file="hu2024wavllm">BIB</button>



# 📖 Education
- *2022.09 - 2025.03 (expected)*, Master of Science in Computer Science and Engineering, Shanghai Jiao Tong University.
- *2018.09 - 2022.06*, Bachelor of Engineering in Computer Science and Engineering, Shanghai Jiao Tong University.


# 💻 Internship
- *2024.01 - present*: [ByteDance](https://www.bytedance.com/en/), Shanghai, China.
- *2023.04 - 2023.11*: [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), Beijing, China.
- *2022.12 - 2023.01*: [Tencent AI Lab](https://ai.tencent.com/ailab/en/index), Shenzhen, China.

# 📖 Service
- Reviewer: ACL Rolling Review (2024), ICME (2024), EMNLP (2023), NLPCC (2022, 2023), CCL (2022, 2023)
- Teaching Assistant: Internet-based Information Extraction Technologies (CS 3307 at SJTU, Fall 2022)


# 🎖 Honors and Awards
- *2023.08*: Optiver Excellent Student Scholarship
- *2022.06*: Best Bachelor Thesis Award
- *2022.06*: Shanghai Jiao Tong University Outstanding Graduates
- *2019, 2020, 2021*: Academic Excellence Scholarship
- *2019*: The first prize of Mathematics Competition of Chinese College Student 

# 💬 Invited Talks
- *2023.06*: Rethinking Translation Memory Augmented Neural Machine Translation, AIS \| [\[slide\]](talks/AIS/AIS-Spot-3.pdf)





<p align="center" style="padding-top: 40px;"><a href='https://clustrmaps.com/site/1bz3w'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=350&t=tt&d=zQTIbvMowu5vzFhApfVkwyYZZQbVqasooVPCbiwEIlo'/></a></p>

