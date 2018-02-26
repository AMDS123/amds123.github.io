---
layout: post
title: "Solving Approximate Wasserstein GANs to Stationarity"
date: 2018-02-22 04:11:58
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Maziar Sanjabi, Jimmy Ba, Meisam Razaviyayn, Jason D. Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) are one of the most practical strategies to learn data distributions. A popular GAN formulation is based on the use of Wasserstein distance as a metric between probability distributions. Unfortunately, minimizing the Wasserstein distance between the data distribution and the generative model distribution is a challenging problem as its objective is non-convex, non-smooth, and even hard to compute. In this work, we propose to use a smooth approximation of the Wasserstein GANs. We show that this smooth approximation is close to the original objective. Moreover, obtaining gradient information of this approximate formulation is computationally effortless and hence one can easily apply first order optimization methods to optimize this objective. Based on this observation, we proposed a class of algorithms with guaranteed theoretical convergence to stationarity. Unlike the original non-smooth objective, our proposed algorithm only requires solving the discriminator to approximate optimality. We applied our method to learning Gaussian mixtures on a grid and also to learning MNIST digits. Our method allows the use of powerful cost functions based on latent representations of the data, where this latent representation could also be optimized adversarially.

##### Abstract (translated by Google)
生成敌对网络（GAN）是学习数据分布的最实用策略之一。流行的GAN公式是基于使用Wasserstein距离作为概率分布之间的度量。不幸的是，最小化数据分布和生成模型分布之间的Wasserstein距离是一个具有挑战性的问题，因为它的目标是非凸的，不光滑的，甚至难以计算。在这项工作中，我们建议使用Wasserstein GAN的平滑近似。我们证明这个平滑的近似值接近于最初的目标。此外，获得该近似公式的梯度信息是计算上不费力的，因此可以容易地应用一阶优化方法来优化该目标。基于这一观察，我们提出了一类保证理论收敛的算法。与原始的非光滑目标不同，我们提出的算法只需要求解鉴别器来近似最优。我们使用我们的方法来学习网格上的高斯混合，并学习MNIST数字。我们的方法允许使用基于数据潜在表示的强大的成本函数，其中该潜在表示也可以被敌对优化。

##### URL
[https://arxiv.org/abs/1802.08249](https://arxiv.org/abs/1802.08249)

##### PDF
[https://arxiv.org/pdf/1802.08249](https://arxiv.org/pdf/1802.08249)

