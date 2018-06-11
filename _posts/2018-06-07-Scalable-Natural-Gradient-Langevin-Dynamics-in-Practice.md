---
layout: post
title: "Scalable Natural Gradient Langevin Dynamics in Practice"
date: 2018-06-07 18:38:15
categories: arXiv_AI
tags: arXiv_AI Adversarial Detection Gradient_Descent Relation
author: Henri Palacci, Henry Hess
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic Gradient Langevin Dynamics (SGLD) is a sampling scheme for Bayesian modeling adapted to large datasets and models. SGLD relies on the injection of Gaussian Noise at each step of a Stochastic Gradient Descent (SGD) update. In this scheme, every component in the noise vector is independent and has the same scale, whereas the parameters we seek to estimate exhibit strong variations in scale and significant correlation structures, leading to poor convergence and mixing times. We compare different preconditioning approaches to the normalization of the noise vector and benchmark these approaches on the following criteria: 1) mixing times of the multivariate parameter vector, 2) regularizing effect on small dataset where it is easy to overfit, 3) covariate shift detection and 4) resistance to adversarial examples.

##### Abstract (translated by Google)
随机梯度Langevin动力学（SGLD）是适用于大数据集和模型的贝叶斯建模的抽样方案。 SGLD在随机梯度下降（SGD）更新的每一步都依赖高斯噪声的注入。在这个方案中，噪声向量中的每个分量都是独立的并且具有相同的尺度，而我们试图估计的参数表现出较大的尺度变化和显着的相关结构，导致收敛和混合时间较差。我们比较了不同的预处理方法对噪声向量的归一化，并且基于以下标准对这些方法进行基准测试：1）多变量参数向量的混合时间，2）容易过度拟合的小数据集的规则化效果，3）协变量移位检测4）抵制敌对的例子。

##### URL
[http://arxiv.org/abs/1806.02855](http://arxiv.org/abs/1806.02855)

##### PDF
[http://arxiv.org/pdf/1806.02855](http://arxiv.org/pdf/1806.02855)

