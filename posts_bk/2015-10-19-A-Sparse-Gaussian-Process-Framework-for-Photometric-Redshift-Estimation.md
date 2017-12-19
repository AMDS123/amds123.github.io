---
layout: post
title: "A Sparse Gaussian Process Framework for Photometric Redshift Estimation"
date: 2015-10-19 16:43:19
categories: arXiv_CV
tags: arXiv_CV Sparse Survey Optimization Inference
author: Ibrahim A. Almosallam, Sam N. Lindsay, Matt J. Jarvis, Stephen J. Roberts
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate photometric redshifts are a lynchpin for many future experiments to pin down the cosmological model and for studies of galaxy evolution. In this study, a novel sparse regression framework for photometric redshift estimation is presented. Simulated and real data from SDSS DR12 were used to train and test the proposed models. We show that approaches which include careful data preparation and model design offer a significant improvement in comparison with several competing machine learning algorithms. Standard implementations of most regression algorithms have as the objective the minimization of the sum of squared errors. For redshift inference, however, this induces a bias in the posterior mean of the output distribution, which can be problematic. In this paper we directly target minimizing $\Delta z = (z_\textrm{s} - z_\textrm{p})/(1+z_\textrm{s})$ and address the bias problem via a distribution-based weighting scheme, incorporated as part of the optimization objective. The results are compared with other machine learning algorithms in the field such as Artificial Neural Networks (ANN), Gaussian Processes (GPs) and sparse GPs. The proposed framework reaches a mean absolute $\Delta z = 0.0026(1+z_\textrm{s})$, over the redshift range of $0 \le z_\textrm{s} \le 2$ on the simulated data, and $\Delta z = 0.0178(1+z_\textrm{s})$ over the entire redshift range on the SDSS DR12 survey, outperforming the standard ANNz used in the literature. We also investigate how the relative size of the training set affects the photometric redshift accuracy. We find that a training set of \textgreater 30 per cent of total sample size, provides little additional constraint on the photometric redshifts, and note that our GP formalism strongly outperforms ANNz in the sparse data regime for the simulated data set.

##### Abstract (translated by Google)
精确的测光红移是未来许多实验的关键，可以确定宇宙模型和星系演化的研究。在这项研究中，提出了一种新的光度红移估计稀疏回归框架。使用来自SDSS DR12的模拟和真实数据来训练和测试所提出的模型。我们表明，包括仔细的数据准备和模型设计的方法提供了一个显着的改善，与几个竞争机器学习算法相比。大多数回归算法的标准实现的目标是最小化平方误差的总和。然而，对于红移推断而言，这导致了产出分布的后验均值的偏差，这可能是有问题的。在本文中，我们直接针对最小化$ \ Delta z =（z_ \ textrm {s}  -  z_ \ textrm {p}）/（1 + z_ \ textrm {s}）$，并通过基于分布的权重方案，作为优化目标的一部分纳入。将结果与人工神经网络（ANN），高斯过程（GP）和稀疏GP等领域的其他机器学习算法进行比较。所提出的框架在模拟数据上的$ 0 \ le z_ \ textrm {s} \ le 2 $的红移范围内达到平均绝对值$ \ Delta z = 0.0026（1 + z_ \ textrm {s}）$，$在SDSS DR12测量的整个红移范围内，Δz= 0.0178（1 + z_ \ textrm {s}）$优于文献中使用的标准ANNz。我们还研究了训练集的相对大小如何影响光度红移精度。我们发现，一个训练样本大小占总样本量的30％，对光度红移几乎没有附加约束，并且注意到我们的GP形式主义在模拟数据集的稀疏数据体制中强于ANNz。

##### URL
[https://arxiv.org/abs/1505.05489](https://arxiv.org/abs/1505.05489)

##### PDF
[https://arxiv.org/pdf/1505.05489](https://arxiv.org/pdf/1505.05489)

