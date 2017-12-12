---
layout: post
title: "VEEGAN: Reducing Mode Collapse in GANs using Implicit Variational Learning"
date: 2017-11-06 21:24:56
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Akash Srivastava, Lazar Valkov, Chris Russell, Michael U. Gutmann, Charles Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
Deep generative models provide powerful tools for distributions over complicated manifolds, such as those of natural images. But many of these methods, including generative adversarial networks (GANs), can be difficult to train, in part because they are prone to mode collapse, which means that they characterize only a few modes of the true distribution. To address this, we introduce VEEGAN, which features a reconstructor network, reversing the action of the generator by mapping from data to noise. Our training objective retains the original asymptotic consistency guarantee of GANs, and can be interpreted as a novel autoencoder loss over the noise. In sharp contrast to a traditional autoencoder over data points, VEEGAN does not require specifying a loss function over the data, but rather only over the representations, which are standard normal by assumption. On an extensive set of synthetic and real world image datasets, VEEGAN indeed resists mode collapsing to a far greater extent than other recent GAN variants, and produces more realistic samples.

##### Abstract (translated by Google)
深度生成模型为复杂流形（如自然图像的分布）提供了强大的工具。但是，包括生成对抗网络（GAN）在内的许多方法可能难以训练，部分原因是它们倾向于模式崩溃，这意味着它们仅表征真实分布的几种模式。为了解决这个问题，我们介绍了VEEGAN，它具有重建网络，通过从数据到噪声的映射反转发生器的动作。我们的训练目标保持了GAN的原始渐近一致性保证，可以解释为一种新型的噪声自动编码器损失。与数据点上的传统自动编码器形成鲜明对比的是，VEEGAN不需要在数据上指定损失函数，而只需要在表示上进行规定，而假设则是标准正态分布。在广泛的合成和真实世界的图像数据集上，VEEGAN确实比其他最近的GAN变体抵抗模式崩溃的程度更高，并产生更逼真的样本。

##### URL
[https://arxiv.org/abs/1705.07761](https://arxiv.org/abs/1705.07761)

##### PDF
[https://arxiv.org/pdf/1705.07761](https://arxiv.org/pdf/1705.07761)

