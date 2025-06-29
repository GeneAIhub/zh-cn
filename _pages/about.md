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



马来亚大学机械工程博士，发表SCI期刊论文5+篇，引用 
<a href='https://scholar.google.com/citations?user=DmN2rEYAAAAJ'>
<img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FGeneAIhub%2FGeneAIhub.github.io%2Fgoogle-scholar-stats%2Fgs_data_shieldsio.json&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>, 导师是 <highlight> <a href="https://umexpert.um.edu.my/alexongzc" target="_blank">Associate Professor Ong Zhi Chao</a></highlight>,<highlight> <a href="https://umexpert.um.edu.my/khooshinyee" target="_blank">Dr. Khoo Shin Yee</a></highlight>，和 <highlight> <a href="https://umexpert.um.edu.my/siowpeiyi" target="_blank">Dr. Siow Pei Yi</a></highlight>.
我们是 <highlight> <a href="https://umengshm.com/asvr/" target="_blank">Advanced Shock and Vibration Research (ASVR) Group</a></highlight>。

研究领域包括: 
- 非线性时间序列分析
- 熵特征提取
- 用于数据增强的生成模型
- 数据不平衡、数据稀缺、标签样本不足等问题
- 小样本学习


[//]: # (# 💻 Work Experiences)

[//]: # (- *2024.09 - Now*&ensp;Postdoctoral researcher in School of Information Science and Technology, University of Science and Technology of China, Hefei, China.)


# 🎓 教育经历 
- * 2023.03 - 至今 博士，机械工程学院，马来亚大学，吉隆坡，马来西亚  <a href="https://engine.um.edu.my/about-mechanical-engineering"><img class="svg" src="/images/UM.png" width="16pt"></a> 
- * 2019.09 - 2022.06 硕士，机械科学与工程学院，东北石油大学，大庆，中国 <a href="https://jxkxygcxy.nepu.edu.cn/"><img class="svg" src="/images/NEPU.png" width="16pt"></a> 

[//]: # (- *2012.09 - 2016.06*&ensp;B.Sc. in School of Electrical Engineering and Automation, Hefei University of Technology, Hefei, China. <a href="https://en.hfut.edu.cn/"><img class="svg" src="/images/hfut.png" width="16pt"></a> )


# 📝 论文
<h3 align="center">2025</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/DSEN.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://www.sciencedirect.com/science/article/pii/S0951832024007142">
            <papertitle> Distance similarity entropy: A sensitive nonlinear feature extraction method for rolling bearing fault diagnosis </papertitle>
        </a>
        <br>
        <strong>Tao Wang</strong>, Shin Yee Khoo, Zhi Chao Ong, Pei Yi Siow, <strong>Teng Wang</strong>.
        <br>
        <em>  Reliability Engineering & System Safety</em>, 2025  <a href="https://github.com/GeneAIhub/GeneAIhub">[code]</a>
        <p></p>
        <p>提出了一种 DSEN 的熵方法，用于轴承故障诊断。该方法通过逐元素距离和高斯相似度捕捉微小的局部变化，并估计相似性分布，从而实现对系统复杂度的精准度量，提升故障诊断的准确性与可靠性。
        </p>
</div>
</div>


<h3 align="center">2025</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/EnSeqInfo.jpg' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://www.sciencedirect.com/science/article/pii/S0952197625007602">
            <papertitle> An enhanced generative adversarial network for longer vibration time data generation under variable operating conditions for imbalanced bearing fault diagnosis </papertitle>
        </a>
        <br>
        <strong>Teng Wang</strong>, Zhi Chao Ong, Shin Yee Khoo, Pei Yi Siow, <strong>Tao Wang</strong>.
        <br>
        <em> Engineering Applications of Artificial Intelligence</em>, 2024 (TOP) <a href="https://github.com/GeneAIhub/GeneAIhub">[code]</a>
        <p></p>
        <p>提出了一种增强型生成对抗网络，用于生成更长的振动时序数据，以改善在变工况下轴承故障诊断中的样本不平衡问题。</p>
    </div>
</div>


<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/SeqInfo.jpg' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://www.sciencedirect.com/science/article/pii/S0263224124022292#f0005">
            <papertitle> SeqInfo-SAWGAN-GP: Adaptive feature extraction from vibration time data under variable operating conditions for imbalanced bearing fault diagnosis </papertitle>
        </a>
        <br>
        <strong>Teng Wang</strong>, Zhi Chao Ong, Shin Yee Khoo, Pei Yi Siow <strong>Tao Wang</strong>.
        <br>
        <em> Measurement</em>, 2024 <a href="https://github.com/Shurun-Wang/GeneAIhub">[code]</a>
        <p></p>
        <p>提出了一种基于序列信息条件的生成模型 SeqInfo-SAWGAN-GP，用于在多变工况下提升合成时间序列数据的多样性，解决故障数据稀缺的问题。</p>
    </div>
</div>

# 🏅 荣誉与奖项
- *2025.03*&ensp;Top 10% SCI论文发表奖励, 工程学院，马来亚大学
- *2024.12*&ensp;Top 10% SCI论文发表奖励, 工程学院，马来亚大学
- *2024.12*&ensp;Top 10% SCI论文发表奖励, 工程学院，马来亚大学
- *2020.12*&ensp;“华为杯”第二十一届中国研究生数学建模竞赛三等奖 — 队长：王桃


# 💪🏸 兴趣爱好
- **健身**  
  进行规律的力量训练与健康管理活动。
  
- **羽毛球**
  - 🥇 2021年 东北石油大学研究生羽毛球团体赛 冠军
  - 🥈 2022年 东北石油大学羽毛球团体赛 亚军
  - 🥈 2024年 建设银行（马来西亚）第二届羽毛球比赛 亚军  
  - 🏆 2024年 马来亚大学国际生男子双打 冠军


# 💬 News
- *Now* &ensp;&ensp;&ensp;&ensp;![Visitors](https://api.visitorbadge.io/api/visitors?path=https://GeneAIhub.github.io/&label=visitors&countColor=%232ccce4&style=plastic)

  



  
