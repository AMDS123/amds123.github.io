---
layout: post
title: "Semi-Amortized Variational Autoencoders"
date: 2018-02-07 18:06:42
categories: arXiv_CL
tags: arXiv_CL Text_Generation Optimization Inference
author: Yoon Kim, Sam Wiseman, Andrew C. Miller, David Sontag, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Amortized variational inference (AVI) replaces instance-specific local inference with a global inference network. While AVI has enabled efficient training of deep generative models such as variational autoencoders (VAE), recent empirical work suggests that inference networks can produce suboptimal variational parameters. We propose a hybrid approach, to use AVI to initialize the variational parameters and run stochastic variational inference (SVI) to refine them. Crucially, the local SVI procedure is itself differentiable, so the inference network and generative model can be trained end-to-end with gradient-based optimization. This semi-amortized approach enables the use of rich generative models without experiencing the posterior-collapse phenomenon common in training VAEs for problems like text generation. Experiments show this approach outperforms strong autoregressive and variational baselines on standard text and image datasets.

##### Abstract (translated by Google)
摊销变分推断（AVI）用全局推理网络取代了实例特定的本地推理。尽管AVI能够对变分自动编码器（VAE）等深层生成模型进行有效的训练，但最近的实证研究表明，推理网络可以产生次优的变分参数。我们提出了一个混合方法，使用AVI来初始化变分参数并运行随机变分推理（SVI）来改进它们。至关重要的是，局部SVI过程本身是可区分的，所以推理网络和生成模型可以通过基于梯度的优化进行端到端的训练。这种半分期的方法能够使用丰富的生成模型，而不会遇到像文本生成这样的问题训练VAE中常见的后坍缩现象。实验表明，这种方法胜过标准文本和图像数据集上的强自回归和变异基线。

##### URL
[https://arxiv.org/abs/1802.02550](https://arxiv.org/abs/1802.02550)

##### PDF
[https://arxiv.org/pdf/1802.02550](https://arxiv.org/pdf/1802.02550)

