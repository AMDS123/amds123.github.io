---
layout: post
title: "Approximability of Discriminators Implies Diversity in GANs"
date: 2018-06-27 17:33:52
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Yu Bai, Tengyu Ma, Andrej Risteski
mathjax: true
---

* content
{:toc}

##### Abstract
While Generative Adversarial Networks (GANs) have empirically produced impressive results on learning complex real-world distributions, recent work has shown that they suffer from lack of diversity or mode collapse. The theoretical work of Arora et al.~\cite{AroraGeLiMaZh17} suggests a dilemma about GANs' statistical properties: powerful discriminators cause overfitting, whereas weak discriminators cannot detect mode collapse. In contrast, we show in this paper that GANs can in principle learn distributions in Wasserstein distance (or KL-divergence in many cases) with polynomial sample complexity, if the discriminator class has strong distinguishing power against the particular generator class (instead of against all possible generators). For various generator classes such as mixture of Gaussians, exponential families, and invertible neural networks generators, we design corresponding discriminators (which are often neural nets of specific architectures) such that the Integral Probability Metric (IPM) induced by the discriminators can provably approximate the Wasserstein distance and/or KL-divergence. This implies that if the training is successful, then the learned distribution is close to the true distribution in Wasserstein distance or KL divergence, and thus cannot drop modes. Our preliminary experiments show that on synthetic datasets the test IPM is well correlated with KL divergence, indicating that the lack of diversity may be caused by the sub-optimality in optimization instead of statistical inefficiency.

##### Abstract (translated by Google)
虽然生成敌对网络（GAN）凭借经验在复杂的现实世界分布中获得了令人印象深刻的结果，但最近的研究表明，它们缺乏多样性或模式崩溃。 Arora等人的理论工作提出了一个关于GANs统计特性的困境：强大的鉴别器导致过拟合，而弱鉴别器不能检测模式崩溃。相反，我们在本文中表明，如果鉴别器类对特定的生成器类具有强大的区分能力（而不是所有的类），那么GANs原则上可以学习Wasserstein距离（或许多情况下的KL-发散）的分布可能的发电机）。对于各种发生器类，如混合高斯函数，指数族和可逆神经网络生成器，我们设计了相应的鉴别器（通常是特定架构的神经网络），使得由鉴别器诱导的积分概率度量（IPM）可以近似地Wasserstein距离和/或KL分歧。这意味着如果训练是成功的，那么学习的分布接近于Wasserstein距离或KL发散的真实分布，因此不能放弃模式。我们的初步实验表明，在合成数据集上，测试IPM与KL散度有很好的相关性，表明缺乏多样性可能是由优化的次优性而不是统计无效性造成的。

##### URL
[https://arxiv.org/abs/1806.10586](https://arxiv.org/abs/1806.10586)

##### PDF
[https://arxiv.org/pdf/1806.10586](https://arxiv.org/pdf/1806.10586)

