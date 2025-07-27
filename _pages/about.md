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

I am a senior student at College of Computer Science and Technology, Southeast University, majoring in Artificial Intelligence, and will graduate from Southeast University with a B.S. in Engineering in 2025! During my undergraduate studies, I was fortunate to be advised by Prof. <a href='https://yangxuntu.github.io/'>Xu Yang</a> and co-work with  <a href='https://github.com/StuHude'>Yicheng Xiao</a> and <a href='https://scholar.google.com/citations?user=smUBVOQAAAAJ&hl=zh-CN'>Ruoxi Cheng.

Additionally, I am an incoming Master student at <a href='https://www.lamda.nju.edu.cn/CH.MainPage.ashx'>LAMDA</a>@Nanjing University, advised by Prof. <a href='https://www.lamda.nju.edu.cn/yehj/'>Hanjia Ye</a>.


<!--
# 🔥 News
- *2024.11*: &nbsp;🎉🎉 I win the **President Scholarship（1%）**!
- *2024.08*: &nbsp;🎉🎉 One paper is accepted by AAAI 2024 Alignment Workshop! 
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by NeurIPS 2024! 
- *2023.07*: &nbsp;🎉🎉 I won a silver medal on Kaggle!

 -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2024 workshop</div><img src='images/rldf.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reinforcement Learning from Multi-role Debates as Feedback for Bias Mitigation in LLMs](https://github.com/Hunter-Wrynn/RLDF)

Ruoxi Cheng†, **Haoxuan Ma†**, Shuirong Cao†, Jiaqi Li, Aihua Pei, Zhiqiang Wang‡, Pengliang Ji, Haoyu Wang, Jiaqi Huo​​
(† Equal contribution,)

[**Project Page**](https://github.com/Hunter-Wrynn/RLDF) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- we propose Reinforcement Learning from Multi-role Debates as Feedback (RLDF), a novel approach for bias mitigation
replacing human feedback in traditional RLHF. We utilize
LLMs in multi-role debates to create a dataset that includes
both high-bias and low-bias instances for training the reward
model in reinforcement learning.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS2024</div><img src='images/leverlm.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Lever LM: Configuring In-Context Sequence to Lever Large Vision Language Models](https://github.com/ForJadeForest/Lever-LM)

Xu Yang, Yingzhe Peng, **Haoxuan Ma**, Shuo Xu, Chi Zhang, Yucheng Han, Hanwang Zhang


[**Project Page**](https://github.com/ForJadeForest/Lever-LM) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- We propose to use a tiny Language Model (LM), e.g., a Transformer with 67M parameters, to lever much larger Vision-Language Models (LVLMs) with 9B parameters. Specifically, we use this tiny Lever-LM to configure effective in-context demonstration (ICD) sequences to improve the In-Context Learinng (ICL) performance of LVLMs
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/drirl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!--

[Inverse Reinforcement Learning with Dynamic Reward Scaling for LLM Alignment](https://hunter-wrynn.github.io/)

Ruoxi Cheng†, **Haoxuan Ma†**, Weixin Wang†, Zhiqiang Wang, Xiaoshuang Jia, Simeng Qin, Xiaochun Cao, Yang Liu, Xiaojun Jia († Equal contribution)

[**Project Page**](https://hunter-wrynn.github.io/) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- we propose DR-IRL, which Dynamically adjusts Rewards through Inverse Reinforcement Learning. We first construct a balanced safety dataset of seven harmful categories using Chain-of-Draft (CoD) template prompts. Then we train category - specific reward models using this dataset as demonstration via IRL. Finally, we propose GRPO-S, Group Relative Policy Optimization-Scaling, a variant of GRPO that scales the reward in optimization to tast difficulty—data-level hardness by CLIP similarity, model-level responsiveness by reward gaps.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/fmla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Masked-image Language Alignment](https://hunter-wrynn.github.io/)

YiCheng Xiao†, Yu Chen†, **Haoxuan Ma†**, Jiale Hong†, Caorui Li, Lingxiang Wu, Zheng Wang, Kuan Zhu, Haiyun Guo, Jinqiao Wang († equal contribution)

[**Project Page**](https://hunter-wrynn.github.io/) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- We propose Fine-grained Masked-image Language Alignment (FMLA), a novel fine-tuning approach that utilizes the local semantic alignment between masks and complex long texts. Our FMLA model can effectively represent images at any granularity (whether local or global) while leveraging the LLM to process complex long texts. This makes it the first model capable of simultaneously meeting demands for local visual prompts input and long text input, consequently overcomes the granularity limitations in both the visual and textual domains.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/segbins.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SegBins: Self-Supervised Monocular Depth Estimation Based On Depth Bins And Semantic Segmentation](https://hunter-wrynn.github.io/)

Yicheng Xiao†, **Haoxuan Ma†**, Zhenhao Shen, Jinfei Qi, RuiFeng Xie, Zixiang Zhang, Haoxiao Wang, Weijie Wang, Peilin Sun, Jiale Hong, Jingyang Fan, Xiaolin Fang, Haiyun Guo, Jinqiao Wang († equal contribution)

[**Project Page**](https://hunter-wrynn.github.io/) <strong><span class='show_paper_citations' data='Hsxmwr0AAAAJ:'></span></strong>
- We propose a new self-supervised monocular depth estimation framework, which innovatively proposes that the framework enhances spatial interaction information and applies multi-layer feature fusion information to extract potential geometric priors of scenes in images, and finally classifies them into multiple depth bin to obtain probabilities, which are combined to form depth. 

</div>
</div>

 -->

# 🎖 Honors and Awards
- *2025.06* Excellent Undergraduate Thesis Award in Southeast University (东南大学优秀毕业论文)
- *2024.11* President Scholarship (top 1%) in Southeast University, $8,000 CNY (校长奖学金)
- *2023.11* Zhishan Scholarship in Southeast University, $3,000 CNY (至善学子奖学金)
- *2023.09* Suzhou Industrial Scholarship in Southeast University, $5,000 CNY (苏州工业园区奖学金)
- *2023.06* Merit Student in Southeast University (东南大学三好学生)
- *2022.11* Zhishan Scholarship in Southeast University, $3,000 CNY (至善学子奖学金)
- *2022.09* Lenovo Research Institute Scholarship in Southeast University, $5,000 CNY (联想研究院奖学金)


# 📖 Educations
- *2021.08 - 2025.06 *, Southeast University, College of Computer Science and Technology.
- *2025.09 - 2028.06 *, Nanjing University, College of Artificial Intelligence.
 
# 💻 Internships
- [Shanghai AI Lab], Trajectory prediction and policy learning in Embodied AI.
- [Huawei ICT], Conducted pretraining and post-training of LLMs.

<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClustrMaps Globe</title>
    <style>
        .map-container {
            width: 25vw; /* 让地图宽度占屏幕 20% */
            margin: 0 auto; /* 水平居中 */
            display: flex;
            justify-content: center;
            align-items: center;
        }
    </style>
</head>
<body>

    <div class="map-container">
        <script type='text/javascript' id='clustrmaps' src='//clustrmaps.com/map_v2.js?d=Jc82Y6nDVcUYKMyNQ1-mgD5LK8xc-Os-55ru7IoVFqY&cl=ffffff&w=a'></script>
    </div>
</body>
</html>
