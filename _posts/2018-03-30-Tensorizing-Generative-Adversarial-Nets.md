---
layout: post
title: "Tensorizing Generative Adversarial Nets"
date: 2018-03-30 03:23:03
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Xingwei Cao, Xuyang Zhao, Qibin Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Network (GAN) and its variants exhibit state-of-the-art performance in the class of generative models. To capture higher-dimensional distributions, the common learning procedure requires high computational complexity and a large number of parameters. The problem of employing such massive framework arises when deploying it on a platform with limited computational power such as mobile phones. In this paper, we present a new generative adversarial framework by representing each layer as a tensor structure connected by multilinear operations, aiming to reduce the number of model parameters by a large factor while preserving the generative performance and sample quality. To learn the model, we employ an efficient algorithm which alternatively optimizes both discriminator and generator. Experimental outcomes demonstrate that our model can achieve high compression rate for model parameters up to $35$ times when compared to the original GAN for MNIST dataset.

##### Abstract (translated by Google)
生成对抗网络（GAN）及其变体在生成模型类中展现了最先进的性能。为了捕获更高维的分布，通用学习过程需要高计算复杂性和大量参数。采用这种大规模框架的问题出现在将其部署在移动电话等计算能力有限的平台上时。在本文中，我们提出了一种新的生成对抗框架，通过将每个层表示为张量结构，通过多线性运算连接起来，目的是在保留生成性能和样本质量的同时，通过大的因子减少模型参数的数量。为了学习模型，我们采用了一种有效的算法，它可以优化鉴别器和发生器。实验结果表明，与最初的MNIST数据集的GAN相比，我们的模型可以实现高达35美元次的模型参数的高压缩率。

##### URL
[http://arxiv.org/abs/1710.10772](http://arxiv.org/abs/1710.10772)

##### PDF
[http://arxiv.org/pdf/1710.10772](http://arxiv.org/pdf/1710.10772)

