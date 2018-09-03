---
layout: post
title: "Spherical Latent Spaces for Stable Variational Autoencoders"
date: 2018-08-31 15:21:05
categories: arXiv_CL
tags: arXiv_CL Face Optimization RNN Language_Model
author: Jiacheng Xu, Greg Durrett
mathjax: true
---

* content
{:toc}

##### Abstract
A hallmark of variational autoencoders (VAEs) for text processing is their combination of powerful encoder-decoder models, such as LSTMs, with simple latent distributions, typically multivariate Gaussians. These models pose a difficult optimization problem: there is an especially bad local optimum where the variational posterior always equals the prior and the model does not use the latent variable at all, a kind of "collapse" which is encouraged by the KL divergence term of the objective. In this work, we experiment with another choice of latent distribution, namely the von Mises-Fisher (vMF) distribution, which places mass on the surface of the unit hypersphere. With this choice of prior and posterior, the KL divergence term now only depends on the variance of the vMF distribution, giving us the ability to treat it as a fixed hyperparameter. We show that doing so not only averts the KL collapse, but consistently gives better likelihoods than Gaussians across a range of modeling conditions, including recurrent language modeling and bag-of-words document modeling. An analysis of the properties of our vMF representations shows that they learn richer and more nuanced structures in their latent representations than their Gaussian counterparts.

##### Abstract (translated by Google)
用于文本处理的变分自动编码器（VAE）的标志是它们强大的编码器 - 解码器模型（例如LSTM）与简单的潜在分布（通常是多变量高斯分布）的组合。这些模型提出了一个困难的优化问题：局部最优，其中变分后验总是等于先验，模型根本不使用潜在变量，这是一种“崩溃”，受到KL分歧项的鼓励。目标。在这项工作中，我们尝试了另一种潜在分布选择，即von Mises-Fisher（vMF）分布，它将质量放置在单位超球面上。通过这种先验和后验的选择，KL分歧项现在仅取决于vMF分布的方差，使我们能够将其视为固定的超参数。我们表明，这样做不仅可以避免KL崩溃，而且在一系列建模条件下，包括循环语言建模和词袋文档建模，始终比高斯人提供更好的可能性。对我们的vMF表示的属性的分析表明，他们在他们的潜在表征中比他们的高斯对应物学习更丰富和更细微的结构。

##### URL
[http://arxiv.org/abs/1808.10805](http://arxiv.org/abs/1808.10805)

##### PDF
[http://arxiv.org/pdf/1808.10805](http://arxiv.org/pdf/1808.10805)

