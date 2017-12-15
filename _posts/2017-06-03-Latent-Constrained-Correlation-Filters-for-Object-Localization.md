---
layout: post
title: "Latent Constrained Correlation Filters for Object Localization"
date: 2017-06-03 09:05:04
categories: arXiv_CV
tags: arXiv_CV Attention Optimization Detection Relation
author: Shangzhen Luan, Baochang Zhang, Jungong Han, Chen Chen, Ling Shao, Alessandro Perina, Linlin Shen
mathjax: true
---

* content
{:toc}

##### Abstract
There is a neglected fact in the traditional machine learning methods that the data sampling can actually lead to the solution sampling. We consider this observation to be important because having the solution sampling available makes the variable distribution estimation, which is a problem in many learning-related applications, more tractable. In this paper, we implement this idea on correlation filter, which has attracted much attention in the past few years due to its high performance with a low computational cost. More specifically, we propose a new method, named latent constrained correlation filters (LCCF) by mapping the correlation filters to a given latent subspace, in which we establish a new learning framework that embeds distribution-related constraints into the original problem. We further introduce a subspace based alternating direction method of multipliers (SADMM) to efficiently solve the optimization problem, which is proved to converge at the saddle point. Our approach is successfully applied to two different tasks inclduing eye localization and car detection. Extensive experiments demonstrate that LCCF outperforms the state-of-the-art methods when samples are suffered from noise and occlusion.

##### Abstract (translated by Google)
传统的机器学习方法存在一个被忽视的事实，即数据采样实际上可能导致解决方案采样。我们认为这个观察是重要的，因为如果有可用的解决方案抽样，可变分布估计在很多与学习有关的应用程序中是一个问题，而且更易于处理。在本文中，我们将这个思想应用到相关滤波器上，由于其高性能和低计算代价，在过去几年引起了人们的广泛关注。更具体地说，我们提出了一种新的方法，称为潜在约束相关滤波器（LCCF），通过将相关滤波器映射到一个给定的潜在子空间，我们建立一个新的学习框架，将分布相关的约束嵌入到原始问题中。进一步引入基于子空间的交替方向乘法器（SADMM）来有效地求解优化问题，证明该方法收敛于鞍点。我们的方法成功应用于两个不同的任务，包括眼睛定位和汽车检测。大量实验证明，当样品受到噪音和堵塞时，LCCF优于最先进的方法。

##### URL
[https://arxiv.org/abs/1606.02170](https://arxiv.org/abs/1606.02170)

##### PDF
[https://arxiv.org/e-print/1606.02170](https://arxiv.org/e-print/1606.02170)

