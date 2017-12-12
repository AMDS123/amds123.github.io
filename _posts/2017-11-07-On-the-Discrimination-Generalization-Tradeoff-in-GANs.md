---
layout: post
title: "On the Discrimination-Generalization Tradeoff in GANs"
date: 2017-11-07 23:45:20
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Pengchuan Zhang, Qiang Liu, Dengyong Zhou, Tao Xu, Xiaodong He
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial training can be generally understood as minimizing certain moment matching loss defined by a set of discriminator functions, typically neural networks. The discriminator set should be large enough to be able to uniquely identify the true distribution (discriminative), and also be small enough to go beyond memorizing samples (generalizable). In this paper, we show that a discriminator set is guaranteed to be discriminative whenever its linear span is dense in the set of bounded continuous functions. This is a very mild condition satisfied even by neural networks with a single neuron. Further, we develop generalization bounds between the learned distribution and true distribution under different evaluation metrics. When evaluated with neural or Wasserstein distances, our bounds show that generalization is guaranteed as long as the discriminator set is small enough, regardless of the size of the generator or hypothesis set. When evaluated with KL divergence, our bound provides an explanation on the counter-intuitive behaviors of testing likelihood in GAN training. Our analysis sheds lights on understanding the practical performance of GANs.

##### Abstract (translated by Google)
生成对抗训练通常可以理解为最小化由一组鉴别器函数（通常为神经网络）定义的特定时刻匹配损失。鉴别器集合应足够大以便能够唯一地识别真实分布（可区分），并且也足够小以至于超出记忆样本（可概化）。在本文中，我们证明了一个鉴别符集在有界连续函数的集合中线性范围是密集的时候保证是有区别的。这是一个非常温和的条件，即使是神经网络与单个神经元满足。进一步，我们在不同的评估指标下发展了学习分布与真实分布之间的泛化界限。当用神经或Wasserstein距离进行评估时，无论发生器或假设集合的大小如何，只要鉴别器集足够小，我们的界限就表明泛化是有保证的。当用KL散度进行评估时，我们的界限提供了在GAN训练中检验可能性的反直觉行为的解释。我们的分析为理解GAN的实际性能提供了亮点。

##### URL
[https://arxiv.org/abs/1711.02771](https://arxiv.org/abs/1711.02771)

##### PDF
[https://arxiv.org/pdf/1711.02771](https://arxiv.org/pdf/1711.02771)

