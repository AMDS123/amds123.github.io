---
layout: post
title: "Amortized Inference Regularization"
date: 2018-05-23 00:14:56
categories: arXiv_AI
tags: arXiv_AI Regularization Represenation_Learning Inference
author: Rui Shu, Hung H. Bui, Shengjia Zhao, Mykel J. Kochenderfer, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
The variational autoencoder (VAE) is a popular model for density estimation and representation learning. Canonically, the variational principle suggests to prefer an expressive inference model so that the variational approximation is accurate. However, it is often overlooked that an overly-expressive inference model can be detrimental to the test set performance of both the amortized posterior approximator and, more importantly, the generative density estimator. In this paper, we leverage the fact that VAEs rely on amortized inference and propose techniques for amortized inference regularization (AIR) that control the smoothness of the inference model. We demonstrate that, by applying AIR, it is possible to improve VAE generalization on both inference and generative performance. Our paper challenges the belief that amortized inference is simply a mechanism for approximating maximum likelihood training and illustrates that regularization of the amortization family provides a new direction for understanding and improving generalization in VAEs.

##### Abstract (translated by Google)
变分自动编码器（VAE）是密度估计和表示学习的流行模型。通常，变分原理建议选择表达性推理模型，以使变分近似精确。然而，经常被忽视的是，过度表达推理模型可能会对摊平后验估计器和更重要的是生成密度估计器的测试集性能产生不利影响。在本文中，我们利用了VAEs依赖于摊销推理的事实，并提出了控制推理模型平滑性的摊销推理正则化（AIR）技术。我们证明，通过应用AIR，可以在推理和生成性能上改进VAE推广。我们的论文质疑认为分期推论只是一种近似最大似然训练的机制，并且说明分期偿债家庭的正规化为理解和改进维和分类中的泛化提供了新的方向。

##### URL
[http://arxiv.org/abs/1805.08913](http://arxiv.org/abs/1805.08913)

##### PDF
[http://arxiv.org/pdf/1805.08913](http://arxiv.org/pdf/1805.08913)

