---
layout: post
title: "Consensus Based Medical Image Segmentation Using Semi-Supervised Learning And Graph Cuts"
date: 2018-05-21 05:36:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Semi_Supervised
author: Dwarikanath Mahapatra
mathjax: true
---

* content
{:toc}

##### Abstract
Medical image segmentation requires consensus ground truth segmentations to be derived from multiple expert annotations. A novel approach is proposed that obtains consensus segmentations from experts using graph cuts (GC) and semi supervised learning (SSL). Popular approaches use iterative Expectation Maximization (EM) to estimate the final annotation and quantify annotator's performance. Such techniques pose the risk of getting trapped in local minima. We propose a self consistency (SC) score to quantify annotator consistency using low level image features. SSL is used to predict missing annotations by considering global features and local image consistency. The SC score also serves as the penalty cost in a second order Markov random field (MRF) cost function optimized using graph cuts to derive the final consensus label. Graph cut obtains a global maximum without an iterative procedure. Experimental results on synthetic images, real data of Crohn's disease patients and retinal images show our final segmentation to be accurate and more consistent than competing methods.

##### Abstract (translated by Google)
医学图像分割需要从多个专家注释中导出共识基础真实分割。提出了一种新颖的方法，使用图形切割（GC）和半监督学习（SSL）从专家获得共识分段。流行的方法使用迭代预期最大化（EM）来估计最终注释并量化注释器的性能。这些技术会造成陷入局部最小值的风险。我们提出一个自我一致性（SC）评分来量化使用低级图像特征的注释器一致性。 SSL用于通过考虑全局特征和本地图像一致性来预测缺失的注释。 SC评分还用作二阶马尔科夫随机场（MRF）成本函数中的罚金成本，该函数使用图形切割优化以得出最终共识标签。图切除在没有迭代过程的情况下获得全局最大值。合成图像的实验结果，克罗恩病患者的真实数据和视网膜图像显示我们的最终分割比相互竞争的方法更准确和更一致。

##### URL
[http://arxiv.org/abs/1612.02166](http://arxiv.org/abs/1612.02166)

##### PDF
[http://arxiv.org/pdf/1612.02166](http://arxiv.org/pdf/1612.02166)

