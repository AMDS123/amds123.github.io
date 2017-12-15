---
layout: post
title: "Photometric Bundle Adjustment for Vision-Based SLAM"
date: 2016-08-05 21:27:11
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Hatem Alismail, Brett Browning, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel algorithm for the joint refinement of structure and motion parameters from image data directly without relying on fixed and known correspondences. In contrast to traditional bundle adjustment (BA) where the optimal parameters are determined by minimizing the reprojection error using tracked features, the proposed algorithm relies on maximizing the photometric consistency and estimates the correspondences implicitly. Since the proposed algorithm does not require correspondences, its application is not limited to corner-like structure; any pixel with nonvanishing gradient could be used in the estimation process. Furthermore, we demonstrate the feasibility of refining the motion and structure parameters simultaneously using the photometric in unconstrained scenes and without requiring restrictive assumptions such as planarity. The proposed algorithm is evaluated on range of challenging outdoor datasets, and it is shown to improve upon the accuracy of the state-of-the-art VSLAM methods obtained using the minimization of the reprojection error using traditional BA as well as loop closure.

##### Abstract (translated by Google)
我们提出了一种新的算法，用于从图像数据直接联合提取结构和运动参数，而不依赖于固定和已知的对应关系。与传统的束调整（BA）相比，最佳参数是通过使用跟踪特征来最小化再投影误差来确定的，所提出的算法依赖于最大化光度一致性并且隐式地估计对应关系。由于所提出的算法不需要对应，所以其应用不限于角状结构;任何非渐变的像素都可以用于估计过程。此外，我们证明了在不受约束的场景中同时使用光度计来精化运动和结构参数的可行性，并且不需要诸如平面度的限制性假设。所提出的算法在具有挑战性的户外数据集的范围上进行评估，并且显示出改进了使用传统BA以及环路闭合使重投影误差最小化而获得的最先进的VSLAM方法的精度。

##### URL
[https://arxiv.org/abs/1608.02026](https://arxiv.org/abs/1608.02026)

##### PDF
[https://arxiv.org/pdf/1608.02026](https://arxiv.org/pdf/1608.02026)

