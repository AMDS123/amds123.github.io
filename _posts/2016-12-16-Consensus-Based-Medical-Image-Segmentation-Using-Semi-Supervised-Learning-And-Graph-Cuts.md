---
layout: post
title: "Consensus Based Medical Image Segmentation Using Semi-Supervised Learning And Graph Cuts"
date: 2016-12-16 04:30:40
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
医学图像分割需要从多个专家注释中获得共识的基础真实分割。提出了一种新的方法，使用图形切割（GC）和半监督学习（SSL）从专家获得共识分割。流行的方法使用迭代期望最大化（EM）来估计最终的注释和量化注释器的性能。这种技术会造成陷入局部最小值的风险。我们提出了自我一致性（SC）评分来量化注释者一致性使用低级别的图像功能。 SSL用于通过考虑全局特征和本地图像一致性来预测缺少的注释。 SC评分也用作二阶马尔可夫随机场（MRF）成本函数中的惩罚代价，其使用图形切割来优化以得出最终共识标签。图切除没有迭代过程获得全局最大值。合成图像的实验结果，克罗恩氏病患者的实际数据和视网膜图像显示我们的最终分割比相互竞争的方法准确和一致。

##### URL
[https://arxiv.org/abs/1612.02166](https://arxiv.org/abs/1612.02166)

##### PDF
[https://arxiv.org/pdf/1612.02166](https://arxiv.org/pdf/1612.02166)

