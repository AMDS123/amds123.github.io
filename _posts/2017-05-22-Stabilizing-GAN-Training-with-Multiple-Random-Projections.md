---
layout: post
title: "Stabilizing GAN Training with Multiple Random Projections"
date: 2017-05-22 16:23:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Behnam Neyshabur, Srinadh Bhojanapalli, Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
Training generative adversarial networks is unstable in high-dimensions when the true data distribution lies on a lower-dimensional manifold. The discriminator is then easily able to separate nearly all generated samples leaving the generator without meaningful gradients. We propose training a single generator simultaneously against an array of discriminators, each of which looks at a different random low-dimensional projection of the data. We show that individual discriminators then provide stable gradients to the generator, and that the generator learns to produce samples consistent with the full data distribution to satisfy all discriminators. We demonstrate the practical utility of this approach experimentally, and show that it is able to produce image samples with higher quality than traditional training with a single discriminator.

##### Abstract (translated by Google)
当真实的数据分布在低维流形上时，训练生成对抗网络在高维上是不稳定的。鉴别器很容易将几乎所有产生的样品离开发生器，而没有有意义的梯度。我们建议同时对一个鉴别器阵列训练一个单一的发生器，每个鉴别器看着数据的不同的随机低维投影。我们证明，个体鉴别器然后为发生器提供稳定的梯度，并且发生器学习产生符合全部数据分布的样本以满足所有的鉴别器。我们通过实验证明了这种方法的实际效用，并且表明它能够产生具有比单个鉴别器的传统训练更高质量的图像样本。

##### URL
[https://arxiv.org/abs/1705.07831](https://arxiv.org/abs/1705.07831)

##### PDF
[https://arxiv.org/pdf/1705.07831](https://arxiv.org/pdf/1705.07831)

