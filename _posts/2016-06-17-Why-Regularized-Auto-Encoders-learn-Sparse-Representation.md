---
layout: post
title: "Why Regularized Auto-Encoders learn Sparse Representation?"
date: 2016-06-17 23:01:20
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Devansh Arpit, Yingbo Zhou, Hung Ngo, Venu Govindaraju
mathjax: true
---

* content
{:toc}

##### Abstract
While the authors of Batch Normalization (BN) identify and address an important problem involved in training deep networks-- \textit{Internal Covariate Shift}-- the current solution has certain drawbacks. For instance, BN depends on batch statistics for layerwise input normalization during training which makes the estimates of mean and standard deviation of input (distribution) to hidden layers inaccurate due to shifting parameter values (especially during initial training epochs). Another fundamental problem with BN is that it cannot be used with batch-size $ 1 $ during training. We address these drawbacks of BN by proposing a non-adaptive normalization technique for removing covariate shift, that we call \textit{Normalization Propagation}. Our approach does not depend on batch statistics, but rather uses a data-independent parametric estimate of mean and standard-deviation in every layer thus being computationally faster compared with BN. We exploit the observation that the pre-activation before Rectified Linear Units follow Gaussian distribution in deep networks, and that once the first and second order statistics of any given dataset are normalized, we can forward propagate this normalization without the need for recalculating the approximate statistics for hidden layers.

##### Abstract (translated by Google)
虽然批量标准化（BN）的作者发现并解决了深度网络培训中涉及的一个重要问题，但是目前的解决方案存在一定的缺陷。例如，BN依赖于批量统计，用于训练期间的分层输入归一化，由于参数值偏移（特别是在初始训练时期），使得输入（分布）到隐藏层的平均值和标准偏差的估计不准确。 BN的另一个基本问题是在培训期间不能使用批量$ 1 $。我们通过提出去除协变量移动的非自适应归一化技术来解决BN的这些缺点，我们称之为\规范化传播}。我们的方法不依赖于批量统计，而是使用与数据无关的每个层中的平均值和标准差的参数估计，因此与BN相比计算速度更快。我们利用了深度网络中整流线性单元之前的预激活遵循高斯分布的观察，并且一旦任何给定数据集的一阶和二阶统计量被归一化，就可以正向传播这种归一化，而不需要重新计算近似统计量为隐藏层。

##### URL
[https://arxiv.org/abs/1505.05561](https://arxiv.org/abs/1505.05561)

##### PDF
[https://arxiv.org/pdf/1505.05561](https://arxiv.org/pdf/1505.05561)

