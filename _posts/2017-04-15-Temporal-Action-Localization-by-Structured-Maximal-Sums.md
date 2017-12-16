---
layout: post
title: "Temporal Action Localization by Structured Maximal Sums"
date: 2017-04-15 18:10:21
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction Detection
author: Zehuan Yuan, Jonathan C. Stroud, Tong Lu, Jia Deng
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of temporal action localization in videos. We pose action localization as a structured prediction over arbitrary-length temporal windows, where each window is scored as the sum of frame-wise classification scores. Additionally, our model classifies the start, middle, and end of each action as separate components, allowing our system to explicitly model each action's temporal evolution and take advantage of informative temporal dependencies present in this structure. In this framework, we localize actions by searching for the structured maximal sum, a problem for which we develop a novel, provably-efficient algorithmic solution. The frame-wise classification scores are computed using features from a deep Convolutional Neural Network (CNN), which are trained end-to-end to directly optimize for a novel structured objective. We evaluate our system on the THUMOS 14 action detection benchmark and achieve competitive performance.

##### Abstract (translated by Google)
我们解决视频中时间动作本地化的问题。我们将动作本地化作为任意长度时间窗口上的结构化预测，其中每个窗口被评分为帧分类分数的总和。此外，我们的模型将每个动作的开始，中间和结束分类为独立的组件，允许我们的系统明确地模拟每个动作的时间演变，并利用此结构中存在的信息时间依赖性。在这个框架中，我们通过搜索结构化最大和来定位行动，这个问题是我们开发一种新颖的，高效的算法解决方案。使用来自深度卷积神经网络（CNN）的特征来计算逐帧分类分数，所述深度卷积神经网络（CNN）被端对端地训练以直接针对新颖的结构化目标进行优化。我们在THUMOS 14行为检测基准上评估我们的系统，并获得有竞争力的表现。

##### URL
[https://arxiv.org/abs/1704.04671](https://arxiv.org/abs/1704.04671)

##### PDF
[https://arxiv.org/pdf/1704.04671](https://arxiv.org/pdf/1704.04671)

