---
layout: post
title: "Lip-Reading Driven Deep Learning Approach for Speech Enhancement"
date: 2018-07-31 19:50:13
categories: arXiv_CV
tags: arXiv_CV RNN Deep_Learning
author: Ahsan Adeel, Mandar Gogate, Amir Hussain, William M. Whitmer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel lip-reading driven deep learning framework for speech enhancement. The proposed approach leverages the complementary strengths of both deep learning and analytical acoustic modelling (filtering based approach) as compared to recently published, comparatively simpler benchmark approaches that rely only on deep learning. The proposed audio-visual (AV) speech enhancement framework operates at two levels. In the first level, a novel deep learning-based lip-reading regression model is employed. In the second level, lip-reading approximated clean-audio features are exploited, using an enhanced, visually-derived Wiener filter (EVWF), for the clean audio power spectrum estimation. Specifically, a stacked long-short-term memory (LSTM) based lip-reading regression model is designed for clean audio features estimation using only temporal visual features considering different number of prior visual frames. For clean speech spectrum estimation, a new filterbank-domain EVWF is formulated, which exploits estimated speech features. The proposed EVWF is compared with conventional Spectral Subtraction and Log-Minimum Mean-Square Error methods using both ideal AV mapping and LSTM driven AV mapping. The potential of the proposed speech enhancement framework is evaluated under different dynamic real-world commercially-motivated scenarios (e.g. cafe, public transport, pedestrian area) at different SNR levels (ranging from low to high SNRs) using benchmark Grid and ChiME3 corpora. For objective testing, perceptual evaluation of speech quality is used to evaluate the quality of restored speech. For subjective testing, the standard mean-opinion-score method is used with inferential statistics. Comparative simulation results demonstrate significant lip-reading and speech enhancement improvement in terms of both speech quality and speech intelligibility.

##### Abstract (translated by Google)
本文提出了一种新颖的唇读驱动深度学习框架，用于语音增强。与最近发布的相对简单的仅依赖于深度学习的基准测试方法相比，所提出的方法利用了深度学习和分析声学建模（基于过滤的方法）的互补优势。拟议的视听（AV）语音增强框架在两个层面上运行。在第一级中，采用了一种新颖的基于深度学习的唇读回归模型。在第二级中，利用增强的，视觉衍生的维纳滤波器（EVWF），利用唇读近似清晰音频特征来进行清晰的音频功率谱估计。具体地，基于堆叠长短期记忆（LSTM）的唇读回归模型被设计用于仅使用考虑不同数量的先前视觉帧的时间视觉特征来进行清晰的音频特征估计。对于干净的语音频谱估计，制定了新的滤波器组域EVWF，其利用估计的语音特征。使用理想的AV映射和LSTM驱动的AV映射，将所提出的EVWF与传统的谱减法和对数最小均方误差方法进行比较。使用基准网格和ChiME3语料库，在不同SNR级别（从低SNR到高SNR）的不同动态真实世界商业动机场景（例如，咖啡馆，公共交通，步行区域）下评估所提出的语音增强框架的潜力。对于客观测试，语音质量的感知评估用于评估恢复的语音的质量。对于主观测试，标准均值 - 意见 - 得分方法与推论统计一起使用。比较模拟结果表明在语音质量和语音清晰度方面显着的唇读和语音增强改善。

##### URL
[https://arxiv.org/abs/1808.00046](https://arxiv.org/abs/1808.00046)

##### PDF
[https://arxiv.org/pdf/1808.00046](https://arxiv.org/pdf/1808.00046)

