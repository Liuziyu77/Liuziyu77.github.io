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

I am currently a student at at <a href='https://www.shlab.org.cn/'>Shanghai AI Laboratory</a> (shlab).

My research interest includes multimodal large language models(MLLMs) and retrieval-argument generation(RAG).



# 🔥 News
- [2024-06-18] Our paper, "MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs," has been rated as the Huggingface **"#1 Paper of the Day"**.
- [2024-06] We are organizing the Visual Perception via Learning in an Open World: The 4th Workshop on Open World Vision and the V3Det Challenge at CVPR 2024.


# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MMDU.png' alt="MMDU" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs](https://arxiv.org/abs/2406.11833)

**Ziyu Liu**, Tao Chu, Yuhang Zang, Xilin Wei, Xiaoyi Dong, Pan Zhang, Zijian Liang, Yuanjun Xiong, Yu Qiao, Dahua Lin, Jiaqi Wang

<span> We introduce MMDU, a comprehensive benchmark, and MMDU-45k, a large-scale instruction tuning dataset, designed to evaluate and improve LVLMs' abilities in multi-turn and multi-image conversations.Our benchmark showcases a conversational setting with a maximum of 20 images and 17 turns. With a maximum of 18k text+image tokens, MMDU evaluates the capacity of LVLMs to process and comprehend extended contextual information with a long context history.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/MMDU)](https://github.com/Liuziyu77/MMDU)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/V3Det_challenge.png' alt="V3Det_challenge" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[V3Det Challenge 2024 on Vast Vocabulary and Open Vocabulary Object Detection: Methods and Results](https://arxiv.org/abs/2406.11739)

Jiaqi Wang, Yuhang Zang, Pan Zhang, Tao Chu, Yuhang Cao, Zeyi Sun, **Ziyu Liu**, Xiaoyi Dong, Tong Wu, Dahua Lin, Zeming Chen, Zhi Wang, Lingchen Meng, Wenhao Yao, Jianwei Yang, Sihong Wu, Zhineng Chen, Zuxuan Wu, Yu-Gang Jiang, Peixi Wu, Bosong Chai, Xuan Nie, Longquan Yan, Zeyu Wang, Qifan Zhou, Boning Wang, Jiaqi Huang, Zunnan Xu, Xiu Li, Kehong Yuan, Yanyan Zu, Jiayao Ha, Qiong Gao, Licheng Jiao

<span> Detecting objects in real-world scenes is a complex task due to various challenges, including the vast range of object categories, and potential encounters with previously unknown or unseen objects. The challenges necessitate the development of public benchmarks and challenges to advance the field of object detection. Inspired by the success of previous COCO and LVIS Challenges, we organize the V3Det Challenge 2024 in conjunction with the 4th Open World Vision Workshop: Visual Perception via Learning in an Open World (VPLOW) at CVPR 2024, Seattle, US. </span>

[**Homepage**](https://v3det.openxlab.org.cn/challenge)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/RAR.png' alt="RAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RAR:Retrieving And Ranking Augmented MLLMs for Visual Recognition](https://arxiv.org/abs/2403.13805)

**Ziyu Liu\***, Zeyi Sun\*, Yuhang Zang, Wei Li, Pan Zhang, Xiaoyi Dong, Yuanjun Xiong, Dahua Lin, Jiaqi Wang

<span> Combining retrieving and ranking with multi-modal large language models to revolutionize perception tasks such as fine-grained recognition, zero-shot image recognition, and few-shot object recognition. Our method opens up new avenues for research in augmenting the MLLM’s abilities with the retrieving-augmented solution and could be beneficial for other tasks such as reasoning and generation in future works.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/RAR)](https://github.com/Liuziyu77/RAR)
</div>
</div>

# 🎖 Honors and Awards
- *2024.06*, Excellent Bachelor's Thesis，Outstanding Undergraduate Graduate of WHU.
- *2023.07*, Meritorious Award, Mathematical Contest in Modeling and Interdisciplinary Contest in Modeling (MCM/ICM), COMAP.
- *2022.05*, National Second Prize, China Undergraduate Mathematical Contest in Modeling(CUMCM), China Society for Industrial and Applied Mathematics(CSIAM).
- *2022.05*, Finalist Award, Mathematical Contest in Modeling and Interdisciplinary Contest in Modeling (MCM/ICM), COMAP.

# 📖 Educations
- *2020.09 - 2024.06*, Undergraduate, Wuhan University. 
