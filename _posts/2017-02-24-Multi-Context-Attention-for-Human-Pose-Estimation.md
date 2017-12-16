---
layout: post
title: "Multi-Context Attention for Human Pose Estimation"
date: 2017-02-24 01:10:53
categories: arXiv_CV
tags: arXiv_CV Salient Attention Pose_Estimation CNN Relation
author: Xiao Chu, Wei Yang, Wanli Ouyang, Cheng Ma, Alan L. Yuille, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to incorporate convolutional neural networks with a multi-context attention mechanism into an end-to-end framework for human pose estimation. We adopt stacked hourglass networks to generate attention maps from features at multiple resolutions with various semantics. The Conditional Random Field (CRF) is utilized to model the correlations among neighboring regions in the attention map. We further combine the holistic attention model, which focuses on the global consistency of the full human body, and the body part attention model, which focuses on the detailed description for different body parts. Hence our model has the ability to focus on different granularity from local salient regions to global semantic-consistent spaces. Additionally, we design novel Hourglass Residual Units (HRUs) to increase the receptive field of the network. These units are extensions of residual units with a side branch incorporating filters with larger receptive fields, hence features with various scales are learned and combined within the HRUs. The effectiveness of the proposed multi-context attention mechanism and the hourglass residual units is evaluated on two widely used human pose estimation benchmarks. Our approach outperforms all existing methods on both benchmarks over all the body parts.

##### Abstract (translated by Google)
在本文中，我们建议将卷积神经网络与多环境关注机制合并到人体姿态估计的端到端框架中。我们采用堆叠式沙漏网络，以多种分辨率和不同语义的特征生成关注地图。利用条件随机场（CRF）对注意图中相邻区域间的相关性进行建模。我们进一步将注重全人体全局一致性的整体注意模型与注重于不同身体部位的详细描述的身体部位注意模型相结合。因此，我们的模型有能力关注从局部显着区域到全局语义一致空间的不同粒度。此外，我们设计新颖的沙漏残留单位（HRUs）来增加网络的接受范围。这些单元是残留单元的扩展，具有包含具有较大接受域的滤波器的侧分支，因此在HRU内学习并结合具有不同尺度的特征。提出的多环境关注机制和沙漏残差单元的有效性在两个广泛使用的人体姿态估计基准上进行评估。我们的方法胜过所有身体部位的所有现有方法。

##### URL
[https://arxiv.org/abs/1702.07432](https://arxiv.org/abs/1702.07432)

##### PDF
[https://arxiv.org/pdf/1702.07432](https://arxiv.org/pdf/1702.07432)

