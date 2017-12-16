---
layout: post
title: "Learning a time-dependent master saliency map from eye-tracking data in videos"
date: 2017-02-02 15:30:55
categories: arXiv_CV
tags: arXiv_CV Salient Tracking
author: Antoine Coutrot, Nathalie Guyader
mathjax: true
---

* content
{:toc}

##### Abstract
To predict the most salient regions of complex natural scenes, saliency models commonly compute several feature maps (contrast, orientation, motion...) and linearly combine them into a master saliency map. Since feature maps have different spatial distribution and amplitude dynamic ranges, determining their contributions to overall saliency remains an open problem. Most state-of-the-art models do not take time into account and give feature maps constant weights across the stimulus duration. However, visual exploration is a highly dynamic process shaped by many time-dependent factors. For instance, some systematic viewing patterns such as the center bias are known to dramatically vary across the time course of the exploration. In this paper, we use maximum likelihood and shrinkage methods to dynamically and jointly learn feature map and systematic viewing pattern weights directly from eye-tracking data recorded on videos. We show that these weights systematically vary as a function of time, and heavily depend upon the semantic visual category of the videos being processed. Our fusion method allows taking these variations into account, and outperforms other state-of-the-art fusion schemes using constant weights over time. The code, videos and eye-tracking data we used for this study are available online: this http URL

##### Abstract (translated by Google)
为了预测复杂自然场景中最显着的区域，显着性模型通常计算几个特征图（对比度，方向，运动...），并将它们线性组合成主显着图。由于特征地图具有不同的空间分布和幅度动态范围，因此确定它们对总体显着性的贡献仍是一个公开的问题。大多数最先进的模型不需要考虑时间，并在整个刺激持续时间内给出特征图的恒定权重。然而，视觉探索是一个由许多时间因素决定的高度动态过程。例如，一些系统的观察模式，如中心偏差，在整个勘探过程中都会发生显着变化。在本文中，我们使用最大似然法和缩小法，从视频上记录的视线数据中直接动态地共同学习特征映射和系统观察模式权重。我们表明，这些权重系统地作为时间的函数而变化，并且很大程度上取决于正在处理的视频的语义视觉类别。我们的融合方法允许考虑到这些变化，并且随着时间的推移使用恒定的权重优于其他现有技术的融合方案。我们用于本研究的代码，视频和眼动数据可以在线获得：http http

##### URL
[https://arxiv.org/abs/1702.00714](https://arxiv.org/abs/1702.00714)

##### PDF
[https://arxiv.org/pdf/1702.00714](https://arxiv.org/pdf/1702.00714)

