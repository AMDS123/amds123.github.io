---
layout: post
title: "Detection of Moving Object in Dynamic Background Using Gaussian Max-Pooling and Segmentation Constrained RPCA"
date: 2017-09-03 03:38:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Yang Li, Guangcan Liu, Shengyong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Due to its efficiency and stability, Robust Principal Component Analysis (RPCA) has been emerging as a promising tool for moving object detection. Unfortunately, existing RPCA based methods assume static or quasi-static background, and thereby they may have trouble in coping with the background scenes that exhibit a persistent dynamic behavior. In this work, we shall introduce two techniques to fill in the gap. First, instead of using the raw pixel-value as features that are brittle in the presence of dynamic background, we devise a so-called Gaussian max-pooling operator to estimate a "stable-value" for each pixel. Those stable-values are robust to various background changes and can therefore distinguish effectively the foreground objects from the background. Then, to obtain more accurate results, we further propose a Segmentation Constrained RPCA (SC-RPCA) model, which incorporates the temporal and spatial continuity in images into RPCA. The inference process of SC-RPCA is a group sparsity constrained nuclear norm minimization problem, which is convex and easy to solve. Experimental results on seven videos from the CDCNET 2014 database show the superior performance of the proposed method.

##### Abstract (translated by Google)
由于其效率和稳定性，鲁棒主成分分析（RPCA）已经成为运动物体检测的一个有前途的工具。不幸的是，现有的基于RPCA的方法假定为静态或准静态背景，因此在处理展示持久动态行为的背景场景时可能会遇到麻烦。在这项工作中，我们将引入两种技术来弥补差距。首先，我们设计一个所谓的高斯最大汇集算子来估计每个像素的“稳定值”，而不是将原始像素值用作存在动态背景的情况下的脆弱特征。这些稳定值对于各种背景变化是稳健的，因此可以有效地区分前景对象和背景。然后，为了获得更准确的结果，我们进一步提出了一个分段约束RPC（SC-RPCA）模型，它将图像中的时间和空间连续性结合到RPCA中。 SC-RPCA推理过程是一个群体稀疏约束的核范数最小化问题，凸性好，易于求解。来自CDCNET 2014数据库的七个视频的实验结果显示了所提出方法的优越性能。

##### URL
[https://arxiv.org/abs/1709.00657](https://arxiv.org/abs/1709.00657)

##### PDF
[https://arxiv.org/pdf/1709.00657](https://arxiv.org/pdf/1709.00657)

