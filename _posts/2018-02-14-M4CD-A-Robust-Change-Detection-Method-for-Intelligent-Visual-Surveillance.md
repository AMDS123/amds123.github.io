---
layout: post
title: "M4CD: A Robust Change Detection Method for Intelligent Visual Surveillance"
date: 2018-02-14 07:51:59
categories: arXiv_CV
tags: arXiv_CV Optimization Detection
author: Kunfeng Wang, Chao Gou, Fei-Yue Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a robust change detection method for intelligent visual surveillance. This method, named M4CD, includes three major steps. Firstly, a sample-based background model that integrates color and texture cues is built and updated over time. Secondly, multiple heterogeneous features (including brightness variation, chromaticity variation, and texture variation) are extracted by comparing the input frame with the background model, and a multi-source learning strategy is designed to online estimate the probability distributions for both foreground and background. The three features are approximately conditionally independent, making multi-source learning feasible. Pixel-wise foreground posteriors are then estimated with Bayes rule. Finally, the Markov random field (MRF) optimization and heuristic post-processing techniques are used sequentially to improve accuracy. In particular, a two-layer MRF model is constructed to represent pixel-based and superpixel-based contextual constraints compactly. Experimental results on the CDnet dataset indicate that M4CD is robust under complex environments and ranks among the top methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种用于智能视觉监控的鲁棒变化检测方法。这种名为M4CD的方法包括三个主要步骤。首先，随着时间的推移构建并更新了集成颜色和纹理提示的基于样本的背景模型。其次，通过比较输入帧和背景模型，提取多种异构特征（包括亮度变化，色度变化和纹理变化），设计多源学习策略在线估计前景和背景的概率分布。这三个特征大致有条件独立，使得多源学习成为可能。然后用Bayes规则估计像素明智的前景后辈。最后，依次使用马尔可夫随机场（MRF）优化和启发式后处理技术来提高准确性。具体而言，构造两层MRF模型以紧凑地表示基于像素和超像素的情境约束。 CDnet数据集上的实验结果表明，M4CD在复杂环境下是稳健的，并且是顶级方法之一。

##### URL
[http://arxiv.org/abs/1802.04979](http://arxiv.org/abs/1802.04979)

##### PDF
[http://arxiv.org/pdf/1802.04979](http://arxiv.org/pdf/1802.04979)

