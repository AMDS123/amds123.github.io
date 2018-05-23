---
layout: post
title: "High-dimension Tensor Completion via Gradient-based Optimization Under Tensor-train Format"
date: 2018-05-22 09:03:23
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Longhao Yuan. Qibin Zhao, Jianting Cao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel approach to recover the missing entries of incomplete data represented by a high-dimension tensor. Tensor-train decomposition, which has powerful tensor representation ability and is free from `the curse of dimensionality', is employed in our approach. By observed entries of incomplete data, we consider to find the factors which can capture the latent features of the data and then reconstruct the missing entries. With low-rank assumption to the original data, tensor completion problem is cast into solving optimization models. Gradient descent methods are applied to optimize the core tensors of tensor-train decomposition. We propose two algorithms: Tensor-train Weighted Optimization (TT-WOPT) and Tensor-train Stochastic Gradient Descent (TT-SGD) to solve tensor completion problems. A high-order tensorization method named visual data tensorization (VDT) is proposed to transform visual data to higher-order forms by which the performance of our algorithms can be improved. The synthetic data experiments and visual data experiments show that our algorithms outperform the state-of-the-art completion algorithms. Especially in high-dimension, high missing rate and large-scale data cases, significant performance can be obtained from our algorithms.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的方法来恢复由高维张量表示的不完整数据的缺失条目。在我们的方法中采用了具有强大张量表示能力并且不存在“维度诅咒”的张量列车分解。通过观察不完整数据的条目，我们考虑找到可以捕获数据的潜在特征的因素，然后重构缺失的条目。通过对原始数据进行低秩假设，张量完成问题被投入解决优化模型。应用梯度下降法来优化张量 - 列车分解的核心张量。我们提出了两种算法：张量加权优化（TT-WOPT）和张量训练随机梯度下降（TT-SGD）来解决张量完成问题。提出了一种高阶张量化方法 - 视觉数据张量化（visual data tensorization，VDT），将视觉数据转化为高阶形式，从而提高算法的性能。合成数据实验和可视化数据实验表明，我们的算法优于最先进的完成算法。特别是在高维度，高丢失率和大规模数据情况下，我们的算法可以获得显着的性能。

##### URL
[http://arxiv.org/abs/1804.01983](http://arxiv.org/abs/1804.01983)

##### PDF
[http://arxiv.org/pdf/1804.01983](http://arxiv.org/pdf/1804.01983)

