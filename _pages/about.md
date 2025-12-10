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

I am currently a Ph.D. student at Shanghai Jiao Tong University (SJTU) under the supervision of <a href='https://scholar.google.com/citations?user=GMzzRRUAAAAJ&hl=en'>Prof. Dahua Lin</a>. I am currently conducting my research at the Shanghai AI Laboratory, where I am jointly advised by <a href='https://yuhangzang.github.io/'>Yuhang Zang</a> and <a href='https://myownskyw7.github.io/'>Jiaqi Wang</a>. My research focuses on Multimodal Large Language Models, Reinforcement Fine-Tuning and Reinforcement Learning, AI Agent, and Reward Model.



# 🔥 News
- [2025-12-09] One paper, RAR, is accepted by IEEE Transactions on Image Processing.
- [2025-06-26] One paper, Visual-RFT, is accepted by ICCV 2025.
- [2025-05-14] One paper, InternLM-XComposer2.5-Reward, is accepted by ACL 2025 Finding.
- [2025-01-23] One paper, MIA-DPO, is accepted by ICLR2025.
- [2024-10-24] One paper, "MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large Vision-Language Models," has been rated as the Huggingface **"#1 Paper of the Day"**.
- [2024-09-28] Two papers, MMDU and MMLONGBENCH-DOC(spotlight), are accepted by NeurIPS2024.
- [2024-06-18] One paper, "MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs," has been rated as the Huggingface **"#1 Paper of the Day"**.
- [2024-06] We are organizing the Visual Perception via Learning in an Open World: The 4th Workshop on Open World Vision and the V3Det Challenge at CVPR 2024.


# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/Visual-ARFT.png' alt="Visual-RFT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visual-ARFT: Visual Agentic Reinforcement Fine-Tuning](https://github.com/Liuziyu77/Visual-RFT/tree/main/Visual-ARFT)

***Ziyu Liu***, Yuhang Zang, Yushan Zou, Zijian Liang, Xiaoyi Dong, Yuhang Cao, Haodong Duan, Dahua Lin, Jiaqi Wang

<span> This work highlights the effectiveness of Visual Agentic Reinforcement Fine-Tuning (Visual-ARFT) for enabling flexible and adaptive reasoning abilities for Large Vision-Language Models (LVLMs). With Visual-ARFT, open-source LVLMs gain the ability to browse websites for real-time information updates and write code to manipulate and analyze input images through cropping, rotation, and other image processing techniques. We also present a Multi-modal Agentic Tool Bench (MAT) with two settings (MAT-Search and MAT-Coding) designed to evaluate LVLMs’ agentic search and coding abilities.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT)](https://github.com/Liuziyu77/Visual-RFT)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/Visual-RFT.png' alt="Visual-RFT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visual-RFT: Visual Reinforcement Fine-Tuning](https://github.com/Liuziyu77/Visual-RFT)***[Accepted by ICCV2025!]***

***Ziyu Liu***, Zeyi Sun, Yuhang Zang, Xiaoyi Dong, Yuhang Cao, Haodong Duan, Dahua Lin, Jiaqi Wang

<span> We introduce Visual Reinforcement Fine-tuning (Visual-RFT), the first comprehensive adaptation of Deepseek-R1's RL strategy to the multimodal field. We use the Qwen2-VL-2/7B model as our base model and design a rule-based verifiable reward, which is integrated into a GRPO-based reinforcement fine-tuning framework to enhance the performance of LVLMs across various visual perception tasks.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT)](https://github.com/Liuziyu77/Visual-RFT)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MIA-DPO.png' alt="MIA-DPO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large Vision-Language Models](https://arxiv.org/abs/2410.17637)***[Accepted by ICLR2025!]***

***Ziyu Liu***, Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Haodong Duan, Conghui He, Yuanjun Xiong, Dahua Lin, Jiaqi Wang

<span> We present Multi-Image Augmented Direct Preference Optimization (MIA-DPO), a visual preference alignment approach that effectively handles multi-image inputs. We use attention values to identify and filter out rejected responses the model may have mistakenly focused on...</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/MIA-DPO)](https://github.com/Liuziyu77/MIA-DPO)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MMDU.png' alt="MMDU" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs](https://arxiv.org/abs/2406.11833) ***[Accepted by NeurIPS2024!]***

***Ziyu Liu***, Tao Chu, Yuhang Zang, Xilin Wei, Xiaoyi Dong, Pan Zhang, Zijian Liang, Yuanjun Xiong, Yu Qiao, Dahua Lin, Jiaqi Wang

<span> We introduce MMDU, a comprehensive benchmark, and MMDU-45k, a large-scale instruction tuning dataset, designed to evaluate and improve LVLMs' abilities in multi-turn and multi-image conversations.Our benchmark showcases a conversational setting with a maximum of 20 images and 17 turns. With a maximum of 18k text+image tokens, MMDU evaluates the capacity of LVLMs to process and comprehend extended contextual information with a long context history.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/MMDU)](https://github.com/Liuziyu77/MMDU)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/RAR.png' alt="RAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RAR:Retrieving And Ranking Augmented MLLMs for Visual Recognition](https://arxiv.org/abs/2403.13805)***[Accepted by IEEE Transactions on Image Processing]***

***Ziyu Liu***, Zeyi Sun, Yuhang Zang, Wei Li, Pan Zhang, Xiaoyi Dong, Yuanjun Xiong, Dahua Lin, Jiaqi Wang

<span> Combining retrieving and ranking with multi-modal large language models to revolutionize perception tasks such as fine-grained recognition, zero-shot image recognition, and few-shot object recognition. Our method opens up new avenues for research in augmenting the MLLM’s abilities with the retrieving-augmented solution and could be beneficial for other tasks such as reasoning and generation in future works.</span>

[**Github** ![](https://img.shields.io/github/stars/Liuziyu77/RAR)](https://github.com/Liuziyu77/RAR)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MMlong.png' alt="RAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMLONGBENCH-DOC: Benchmarking Long-context Document Understanding with Visualizations](https://arxiv.org/abs/2407.01523) ***[Accepted by NeurIPS2024!(Spotlight)]***

Yubo Ma, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, ***Ziyu Liu***, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-Gang Jiang, Jiaqi Wang, Yixin Cao, Aixin Sun

[**Github** ![](https://img.shields.io/github/stars/mayubo2333/MMLongBench-Doc)](https://github.com/mayubo2333/MMLongBench-Doc)
</div>
</div>


# 🎖 Honors and Awards
- *2024.06*, Excellent Bachelor's Thesis，Outstanding Undergraduate Graduate.
- *2023.07*, Meritorious Award, Mathematical Contest in Modeling and Interdisciplinary Contest in Modeling (MCM/ICM), COMAP.
- *2022.05*, National Second Prize, China Undergraduate Mathematical Contest in Modeling(CUMCM), China Society for Industrial and Applied Mathematics(CSIAM).
- *2022.05*, Finalist Award, Mathematical Contest in Modeling and Interdisciplinary Contest in Modeling (MCM/ICM), COMAP.

# 📖 Educations
- *2024.09 - until now*, PHD, Shanghai Jiao Tong University.

# 📌 Activities
- Reviewer of ICLR2025, ICLR2026, Neurips2024, NeurIPS2025 (Top Reviewer), CVPR, TMM. 
- Workshop organizing community of <a href='https://vplow.github.io/vplow_4th.html'>VPLOW@CVPR2024</a>
