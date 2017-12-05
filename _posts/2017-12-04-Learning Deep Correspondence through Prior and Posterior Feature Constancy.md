---
layout: post
title: 'Learning Deep Correspondence through Prior and Posterior Feature Constancy'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: arXiv_CV
author: Zhengfa Liang, Yiliu Feng, Yulan Guo, Hengzhu Liu, Linbo Qiao, Wei Chen, Li Zhou, Jianfeng Zhang
---

* content
{:toc}

##### Abstract
Stereo matching algorithms usually consist of four steps, including matching cost calculation, matching cost aggregation, disparity calculation, and disparity refinement. Existing CNN-based methods only adopt CNN to solve parts of the four steps, or use different networks to deal with different steps, making them difficult to obtain the overall optimal solution. In this paper, we propose a network architecture to incorporate all steps of stereo matching. The network consists of three parts. The first part calculates the multi-scale shared features. The second part performs matching cost calculation, matching cost aggregation and disparity calculation to estimate the initial disparity using shared features. The initial disparity and the shared features are used to calculate the prior and posterior feature constancy. The initial disparity, the prior and posterior feature constancy are then fed to a sub-network to refine the initial disparity through a Bayesian inference process. The proposed method has been evaluated on the Scene Flow and KITTI datasets. It achieves the state-of-the-art performance on the KITTI 2012 and KITTI 2015 benchmarks while maintaining a very fast running time.

##### Abstract (translated by Google)
立体匹配算法通常包括四个步骤，包括匹配成本计算，匹配成本聚合，差异计算和差异细化。现有的基于CNN的方法仅采用CNN来解决四个步骤中的部分问题，或者采用不同的网络来处理不同的步骤，使得难以获得整体的最优解。在本文中，我们提出了一个网络体系结构来整合立体匹配的所有步骤。网络由三部分组成。第一部分计算多尺度共享特征。第二部分进行匹配成本计算，匹配成本聚合和差异计算，利用共享特征估计初始视差。使用初始视差和共享特征来计算先验和后验特征恒定性。然后将初始视差，先验和后验特征恒定性馈送到子网络，以通过贝叶斯推断过程来细化初始视差。所提出的方法已经在场景流和KITTI数据集上进行了评估。它在KITTI 2012和KITTI 2015基准测试中达到了最先进的性能，同时保持了非常快的运行时间。

##### URL
[http://arxiv.org/abs/1712.01039](http://arxiv.org/abs/1712.01039)

