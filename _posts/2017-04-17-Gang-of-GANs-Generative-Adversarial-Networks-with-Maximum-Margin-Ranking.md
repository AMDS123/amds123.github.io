---
layout: post
title: "Gang of GANs: Generative Adversarial Networks with Maximum Margin Ranking"
date: 2017-04-17 04:42:56
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Felix Juefei-Xu, Vishnu Naresh Boddeti, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional generative adversarial networks (GAN) and many of its variants are trained by minimizing the KL or JS-divergence loss that measures how close the generated data distribution is from the true data distribution. A recent advance called the WGAN based on Wasserstein distance can improve on the KL and JS-divergence based GANs, and alleviate the gradient vanishing, instability, and mode collapse issues that are common in the GAN training. In this work, we aim at improving on the WGAN by first generalizing its discriminator loss to a margin-based one, which leads to a better discriminator, and in turn a better generator, and then carrying out a progressive training paradigm involving multiple GANs to contribute to the maximum margin ranking loss so that the GAN at later stages will improve upon early stages. We call this method Gang of GANs (GoGAN). We have shown theoretically that the proposed GoGAN can reduce the gap between the true data distribution and the generated data distribution by at least half in an optimally trained WGAN. We have also proposed a new way of measuring GAN quality which is based on image completion tasks. We have evaluated our method on four visual datasets: CelebA, LSUN Bedroom, CIFAR-10, and 50K-SSFF, and have seen both visual and quantitative improvement over baseline WGAN.

##### Abstract (translated by Google)
传统的生成对抗网络（GAN）及其许多变体是通过最小化KL或JS-发散性损失来进行训练的，这种损失衡量的是生成的数据分布与真实数据分布的接近程度。基于Wasserstein距离的最近的一个叫做WGAN的预测可以改进基于KL和JS-发散的GAN，并且减轻在GAN训练中常见的梯度消失，不稳定性和模式崩溃问题。在这项工作中，我们的目标是通过首先将其鉴别器损失推广到基于边缘的鉴别器来改进WGAN，这导致更好的鉴别器，并进而产生更好的发生器，然后执行涉及多个GAN的渐进式训练范例导致最大的利润率排名损失，从而使后期的GAN在早期阶段得到改善。我们把这个方法称为GANs（GoGAN）。我们从理论上已经表明，所提出的GoGAN可以在经过最优训练的WGAN中将真实的数据分布和所产生的数据分布之间的差距减少至少一半。我们也提出了一种基于图像完成任务的测量GAN质量的新方法。我们已经在四个视觉数据集上评估了我们的方法：CelebA，LSUN卧室，CIFAR-10和50K-SSFF，并且已经在基线WGAN上看到了视觉和数量的改善。

##### URL
[https://arxiv.org/abs/1704.04865](https://arxiv.org/abs/1704.04865)

##### PDF
[https://arxiv.org/pdf/1704.04865](https://arxiv.org/pdf/1704.04865)

