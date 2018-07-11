---
layout: post
title: "Latent Alignment and Variational Attention"
date: 2018-07-10 16:59:12
categories: arXiv_CL
tags: arXiv_CL Attention Inference VQA
author: Yuntian Deng, Yoon Kim, Justin Chiu, Demi Guo, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Neural attention has become central to many state-of-the-art models in natural language processing and related domains. Attention networks are an easy-to-train and effective method for softly simulating alignment; however, the approach does not marginalize over latent alignments in a probabilistic sense. This property makes it difficult to compare attention to other alignment approaches, to compose it with probabilistic models, and to perform posterior inference conditioned on observed data. A related latent approach, hard attention, fixes these issues, but is generally harder to train and less accurate. This work considers variational attention networks, alternatives to soft and hard attention for learning latent variable alignment models, with tighter approximation bounds based on amortized variational inference. We further propose methods for reducing the variance of gradients to make these approaches computationally feasible. Experiments show that for machine translation and visual question answering, inefficient exact latent variable models outperform standard neural attention, but these gains go away when using hard attention based training. On the other hand, variational attention retains most of the performance gain but with training speed comparable to neural attention.

##### Abstract (translated by Google)
神经注意已经成为自然语言处理和相关领域中许多最先进模型的核心。注意网络是一种易于训练和有效的方法，用于软模拟对齐;然而，这种方法并没有在概率意义上对潜在的对齐进行边缘化。该属性使得难以将注意力与其他对齐方法进行比较，将其与概率模型组合，并且以观察到的数据为基础进行后验推断。一个相关的潜在方法，强烈关注，解决了这些问题，但通常难以训练和不太准确。这项工作考虑了变分注意网络，学习潜变量对齐模型的软和硬注意的替代方案，基于摊销的变分推理具有更严格的近似界限。我们进一步提出了用于减小梯度方差的方法，以使这些方法在计算上可行。实验表明，对于机器翻译和视觉问题回答，低效的精确潜变量模型优于标准神经注意，但是当使用基于硬注意力的训练时，这些收益会消失。另一方面，变分注意力保留了大部分的性能提升，但训练速度与神经注意力相当。

##### URL
[http://arxiv.org/abs/1807.03756](http://arxiv.org/abs/1807.03756)

##### PDF
[http://arxiv.org/pdf/1807.03756](http://arxiv.org/pdf/1807.03756)

