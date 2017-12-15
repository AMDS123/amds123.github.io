---
layout: post
title: "Online Learning to Sample"
date: 2016-03-15 16:08:56
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Image_Classification Optimization Classification Gradient_Descent
author: Guillaume Bouchard, Théo Trouillon, Julien Perez, Adrien Gaidon
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic Gradient Descent (SGD) is one of the most widely used techniques for online optimization in machine learning. In this work, we accelerate SGD by adaptively learning how to sample the most useful training examples at each time step. First, we show that SGD can be used to learn the best possible sampling distribution of an importance sampling estimator. Second, we show that the sampling distribution of an SGD algorithm can be estimated online by incrementally minimizing the variance of the gradient. The resulting algorithm - called Adaptive Weighted SGD (AW-SGD) - maintains a set of parameters to optimize, as well as a set of parameters to sample learning examples. We show that AWSGD yields faster convergence in three different applications: (i) image classification with deep features, where the sampling of images depends on their labels, (ii) matrix factorization, where rows and columns are not sampled uniformly, and (iii) reinforcement learning, where the optimized and exploration policies are estimated at the same time, where our approach corresponds to an off-policy gradient algorithm.

##### Abstract (translated by Google)
随机梯度下降（SGD）是机器学习中在线优化中使用最广泛的技术之一。在这项工作中，我们通过自适应学习如何在每个时间步骤对最有用的训练样本进行抽样来加速SGD。首先，我们证明SGD可以用来学习重要抽样估计量的最佳抽样分布。其次，我们证明一个SGD算法的抽样分布可以通过增量最小化梯度的方差来在线估计。由此产生的称为自适应加权SGD（AW-SGD）的算法维护一组参数以进行优化，以及一组参数来对学习示例进行示例。我们展示了AWSGD在三个不同的应用中产生更快的收敛：（i）具有深度特征的图像分类，其中图像的采样取决于其标签;（ii）矩阵分解，其中行和列不被均匀采样;强化学习，其中优化和探索策略是在同一时间估计的，其中我们的方法对应于关闭策略梯度算法。

##### URL
[https://arxiv.org/abs/1506.09016](https://arxiv.org/abs/1506.09016)

##### PDF
[https://arxiv.org/pdf/1506.09016](https://arxiv.org/pdf/1506.09016)

