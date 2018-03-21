---
layout: post
title: "MAGSAC: marginalizing sample consensus"
date: 2018-03-20 15:01:11
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Daniel Barath, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
A method called sigma-consensus is proposed to eliminate the need for a user-defined inlier-outlier threshold in RANSAC. Instead of estimating sigma, it is marginalized over a range of noise scales using a Bayesian estimator, i.e. the optimized model is obtained as the weighted average using the posterior probabilities as weights. Applying sigma-consensus, two methods are proposed: (i) a post-processing step which always improved the model quality on a wide range of vision problems without noticeable deterioration in processing time, i.e. at most 1-2 milliseconds; and (ii) a locally optimized RANSAC, called LO-MAGSAC, which includes sigma-consensus to the local optimization of LO-RANSAC. The method is superior to the state-of-the-art in terms of geometric accuracy on publicly available real world datasets for epipolar geometry (F and E), homography and affine transformation estimation.

##### Abstract (translated by Google)
提出了一种称为sigma-consensus的方法，以消除在RANSAC中对用户定义的inlier-outlier阈值的需求。使用贝叶斯估计器，而不是估计西格玛，它在一系列噪声尺度上被边缘化，即使用后验概率作为权重获得优化模型作为加权平均值。应用西格玛共识，提出了两种方法：（i）后处理步骤，其总是在广泛的视觉问题上改善模型质量，而处理时间没有明显的劣化，即最多1-2毫秒;和（ii）本地优化的RANSAC，称为LO-MAGSAC，其包括对LO-RANSAC的本地优化的西格玛共识。在对极几何（F和E），单应性和仿射变换估计的公开可用的真实世界数据集上的几何精度方面，该方法优于现有技术。

##### URL
[http://arxiv.org/abs/1803.07469](http://arxiv.org/abs/1803.07469)

##### PDF
[http://arxiv.org/pdf/1803.07469](http://arxiv.org/pdf/1803.07469)

