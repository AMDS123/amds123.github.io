---
layout: post
title: "GANs Trained by a Two Time-Scale Update Rule Converge to a Local Nash Equilibrium"
date: 2017-11-08 16:25:21
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Gradient_Descent
author: Martin Heusel, Hubert Ramsauer, Thomas Unterthiner, Bernhard Nessler, Sepp Hochreiter
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) excel at creating realistic images with complex models for which maximum likelihood is infeasible. However, the convergence of GAN training has still not been proved. We propose a two time-scale update rule (TTUR) for training GANs with stochastic gradient descent on arbitrary GAN loss functions. TTUR has an individual learning rate for both the discriminator and the generator. Using the theory of stochastic approximation, we prove that the TTUR converges under mild assumptions to a stationary local Nash equilibrium. The convergence carries over to the popular Adam optimization, for which we prove that it follows the dynamics of a heavy ball with friction and thus prefers flat minima in the objective landscape. For the evaluation of the performance of GANs at image generation, we introduce the "Fr\'echet Inception Distance" (FID) which captures the similarity of generated images to real ones better than the Inception Score. In experiments, TTUR improves learning for DCGANs and Improved Wasserstein GANs (WGAN-GP) outperforming conventional GAN training on CelebA, CIFAR-10, SVHN, LSUN Bedrooms, and the One Billion Word Benchmark.

##### Abstract (translated by Google)
生成敌对网络（GANs）擅长用最复杂的模型创建逼真的图像，而最大的可能性是不可行的。但是，GAN训练的收敛性尚未得到证实。我们提出了一种两时间尺度更新规则（TTUR），用于训练具有随机梯度下降的随机GAN损失函数的GAN。 TTUR对于鉴别器和发生器都具有单独的学习速率。利用随机逼近理论，证明了TTUR在温和假设下收敛于一个平稳的局部纳什均衡。这种融合延续到流行的亚当优化中，为此我们证明它遵循了摩擦重球的动力学，因此更喜欢客观景观中的平坦最小值。为了评估GAN在图像生成中的性能，我们引入了“生成距离”（FID），该生成的图像与生成图像的相似性比起始分数更好。在实验中，TTUR提高了对DCGANs和改进的Wasserstein GANs（WGAN-GP）的学习，其表现优于传统的CelebA，CIFAR-10，SVHN，LSUN房间和十亿字基准的GAN培训。

##### URL
[https://arxiv.org/abs/1706.08500](https://arxiv.org/abs/1706.08500)

##### PDF
[https://arxiv.org/pdf/1706.08500](https://arxiv.org/pdf/1706.08500)

