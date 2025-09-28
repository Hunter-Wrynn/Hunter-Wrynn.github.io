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

I am presently pursuing my graduate studies at  <a href='https://www.lamda.nju.edu.cn/CH.MainPage.ashx'>LAMDA</a>@Nanjing University, advised by Prof. <a href='https://www.lamda.nju.edu.cn/yehj/'>Hanjia Ye</a>.

Currently, I focus on Model Reuse and Agentic RL. I am also interested in LLMs for recommending systems and quantitative trading.

For collaboration and inquiries, contact: hunterwrynn AT gmail DOT com

<!--
# 🔥 News

- *2024.11*: &nbsp;🎉🎉 I win the **President Scholarship（1%）**!
- *2024.08*: &nbsp;🎉🎉 One paper is accepted by AAAI 2024 Alignment Workshop! 
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by NeurIPS 2024! 
- *2023.07*: &nbsp;🎉🎉 I won a silver medal on Kaggle!

 -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS2024 workshop</div><img src='images/rldf.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reinforcement Learning from Multi-role Debates as Feedback for Bias Mitigation in LLMs](https://github.com/Hunter-Wrynn/RLDF)

Ruoxi Cheng†, **Haoxuan Ma†**, Shuirong Cao†
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

 
# 🎖 Honors and Awards
- *2024.11* President Scholarship (top 1%) in Southeast University


 
# 📖 Educations
- *2021.08 - 2025.06 *, Southeast University, College of Computer Science and Technology.
- *2025.09 - 2028.06 *, Nanjing University, College of Artificial Intelligence.
 
# 💻 Internships
- [Shanghai AI Lab], Trajectory prediction and policy learning in Embodied AI.
- [Huawei ICT], LLM post-training.

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
        <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=300&t=tt&d=Jc82Y6nDVcUYKMyNQ1-mgD5LK8xc-Os-55ru7IoVFqY&co=b3b3b3&ct=808080&cmo=3acc3a&cmn=ff5353'></script>
    </div>
</body>
</html>
