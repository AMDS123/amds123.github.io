---
layout: post
title: "Latent Constrained Correlation Filter"
date: 2017-11-11 20:27:39
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Optimization Detection Relation Recognition
author: Baochang Zhang, Shangzhen Luan, Chen Chen, Jungong Han, Wei Wang, Alessandro Perina, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filters are special classifiers designed for shift-invariant object recognition, which are robust to pattern distortions. The recent literature shows that combining a set of sub-filters trained based on a single or a small group of images obtains the best performance. The idea is equivalent to estimating variable distribution based on the data sampling (bagging), which can be interpreted as finding solutions (variable distribution approximation) directly from sampled data space. However, this methodology fails to account for the variations existed in the data. In this paper, we introduce an intermediate step -- solution sampling -- after the data sampling step to form a subspace, in which an optimal solution can be estimated. More specifically, we propose a new method, named latent constrained correlation filters (LCCF), by mapping the correlation filters to a given latent subspace, and develop a new learning framework in the latent subspace that embeds distribution-related constraints into the original problem. To solve the optimization problem, we introduce a subspace based alternating direction method of multipliers (SADMM), which is proven to converge at the saddle point. Our approach is successfully applied to three different tasks, including eye localization, car detection and object tracking. Extensive experiments demonstrate that LCCF outperforms the state-of-the-art methods. The source code will be publicly available. this https URL

##### Abstract (translated by Google)
相关滤波器是为移位不变对象识别设计的特殊分类器，对模式失真具有鲁棒性。最近的文献显示，组合一组基于单个或一组图像训练的子滤波器获得最佳性能。这个想法等同于基于数据采样（bagging）来估计可变分布，其可以被解释为直接从采样数据空间求解（可变分布近似）。但是，这种方法没有考虑到数据中存在的变化。在本文中，我们介绍了一个中间步骤 - 解决方案抽样 - 在数据采样步骤后形成一个子空间，其中可以估计一个最佳的解决方案。更具体地说，我们提出了一种新的方法，称为潜在约束相关滤波器（LCCF），通过将相关滤波器映射到一个给定的潜在子空间，并在潜在子空间中开发一个新的学习框架，将分布相关的约束嵌入到原始问题中。为了解决优化问题，我们引入了一种基于子空间的乘法器交替方向（SADMM）方法，证明该方法在鞍点上收敛。我们的方法被成功应用于三个不同的任务，包括眼睛定位，汽车检测和对象跟踪。大量的实验表明，LCCF优于最先进的方法。源代码将公开可用。这个https网址

##### URL
[https://arxiv.org/abs/1711.04192](https://arxiv.org/abs/1711.04192)

##### PDF
[https://arxiv.org/pdf/1711.04192](https://arxiv.org/pdf/1711.04192)

