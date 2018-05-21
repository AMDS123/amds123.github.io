---
layout: post
title: "GumBolt: Extending Gumbel trick to Boltzmann priors"
date: 2018-05-18 17:59:17
categories: arXiv_AI
tags: arXiv_AI
author: Amir H. Khoshaman, Mohammad H. Amin
mathjax: true
---

* content
{:toc}

##### Abstract
Boltzmann machines (BMs) are appealing candidates for powerful priors in variational autoencoders (VAEs), as they are capable of capturing nontrivial and multi-modal distributions over discrete variables. However, indifferentiability of the discrete units prohibits using the reparameterization trick, essential for low-noise back propagation. The Gumbel trick resolves this problem in a consistent way by relaxing the variables and distributions, but it is incompatible with BM priors. Here, we propose the GumBolt, a model that extends the Gumbel trick to BM priors in VAEs. GumBolt is significantly simpler than the recently proposed methods with BM prior and outperforms them by a considerable margin. It achieves state-of-the-art performance on permutation invariant MNIST and OMNIGLOT datasets in the scope of models with only discrete latent variables. Moreover, the performance can be further improved by allowing multi-sampled (importance-weighted) estimation of log-likelihood in training, which was not possible with previous models.

##### Abstract (translated by Google)
玻尔兹曼机（BMS）是用于变自动编码强大先验（VAES）吸引人的候选，因为它们能够在离散变量捕获非平凡和多模态分布。但是，离散单元的不可分性禁止使用重新参数化技巧，这对于低噪声反向传播是必不可少的。 Gumbel技巧通过放松变量和分布来以一致的方式解决这个问题，但它与BM先验不相容。在这里，我们提出GumBolt模型，它将Gumbel技巧扩展到VAE中的BM先验。 GumBolt比最近提出的BM先验方法简单得多，并且在相当大的范围内胜过了它们。它在排列不变的MNIST和OMNIGLOT数据集上实现了最先进的性能，仅在具有离散潜变量的模型范围内。此外，通过允许对训练中的对数似然的多重采样（重要性加权）估计来进一步改进性能，这在以前的模型中是不可能的。

##### URL
[http://arxiv.org/abs/1805.07349](http://arxiv.org/abs/1805.07349)

##### PDF
[http://arxiv.org/pdf/1805.07349](http://arxiv.org/pdf/1805.07349)

