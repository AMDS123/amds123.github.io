---
layout: post
title: "Meta-Learning Priors for Efficient Online Bayesian Regression"
date: 2018-07-24 05:46:04
categories: arXiv_RO
tags: arXiv_RO Prediction
author: James Harrison, Apoorva Sharma, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian Process (GP) regression has seen widespread use in robotics due to its generality, simplicity of use, and the utility of Bayesian predictions. In particular, the predominant implementation of GP regression is kernel-based, as it enables fitting of arbitrary nonlinear functions by leveraging kernel functions as infinite-dimensional features. While incorporating prior information has the potential to drastically improve data efficiency of kernel-based GP regression, expressing complex priors through the choice of kernel function and associated hyperparameters is often challenging and unintuitive. Furthermore, the computational complexity of kernel-based GP regression scales poorly with the number of samples, limiting its application in regimes where a large amount of data is available. In this work, we propose ALPaCA, an algorithm for efficient Bayesian regression which addresses these issues. ALPaCA uses a dataset of sample functions to learn a domain-specific, finite-dimensional feature encoding, as well as a prior over the associated weights, such that Bayesian linear regression in this feature space yields accurate online predictions of the posterior density. These features are neural networks, which are trained via a meta-learning approach. ALPaCA extracts all prior information from the dataset, rather than relying on the choice of arbitrary, restrictive kernel hyperparameters. Furthermore, it substantially reduces sample complexity, and allows scaling to large systems. We investigate the performance of ALPaCA on two simple regression problems, two simulated robotic systems, and on a lane-change driving task performed by humans. We find our approach outperforms kernel-based GP regression, as well as state of the art meta-learning approaches, thereby providing a promising plug-in tool for many regression tasks in robotics where scalability and data-efficiency are important.

##### Abstract (translated by Google)
高斯过程（GP）回归由于其通用性，使用简单性和贝叶斯预测的效用而在机器人技术中得到广泛应用。特别是，GP回归的主要实现是基于内核的，因为它可以通过利用内核函数作为无限维特征来拟合任意非线性函数。虽然结合先验信息有可能大大提高基于内核的GP回归的数据效率，但通过选择内核函数和相关的超参数来表达复杂的先验通常具有挑战性且不直观。此外，基于内核的GP回归的计算复杂性随着样本数量的不足而缩小，限制了其在可获得大量数据的方案中的应用。在这项工作中，我们提出了ALPaCA，一种有效的贝叶斯回归算法，可以解决这些问题。 ALPaCA使用样本函数的数据集来学习特定于域的有限维特征编码，以及相关权重之前的先验，使得该特征空间中的贝叶斯线性回归产生后验密度的准确在线预测。这些特征是神经网络，通过元学习方法进行训练。 ALPaCA从数据集中提取所有先验信息，而不是依赖于任意限制性内核超参数的选择。此外，它大大降低了样本复杂性，并允许扩展到大型系统。我们研究了ALPaCA在两个简单的回归问题，两个模拟机器人系统以及人类执行的车道变换驾驶任务上的表现。我们发现我们的方法优于基于内核的GP回归以及最先进的元学习方法，从而为机器人中的许多回归任务提供了一种有前途的插件工具，其中可扩展性和数据效率非常重要。

##### URL
[http://arxiv.org/abs/1807.08912](http://arxiv.org/abs/1807.08912)

##### PDF
[http://arxiv.org/pdf/1807.08912](http://arxiv.org/pdf/1807.08912)

