---
layout: post
title: "Demystifying MMD GANs"
date: 2018-01-04 15:25:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Mikołaj Bińkowski, Dougal J. Sutherland, Michael Arbel, Arthur Gretton
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the training and performance of generative adversarial networks using the Maximum Mean Discrepancy (MMD) as critic, termed MMD GANs. As our main theoretical contribution, we clarify the situation with bias in GAN loss functions raised by recent work: we show that gradient estimators used in the optimization process for both MMD GANs and Wasserstein GANs are unbiased, while gradients of the generator's theoretical loss are biased in both cases. We discuss the issue of kernel choice for the MMD critic, and characterize the kernel corresponding to the energy distance used for the Cram\'er GAN critic. Being an integral probability metric, the MMD benefits from training strategies recently developed for Wasserstein GANs. In experiments, the MMD GAN is able to employ a smaller critic network than the Wasserstein GAN, resulting in a simpler and faster-training algorithm with matching performance. We also propose an improved measure of GAN convergence, the Kernel Inception Distance, and show how to use it to dynamically adapt learning rates during GAN training.

##### Abstract (translated by Google)
我们使用最大均值差异（MMD）作为评论者，称为MMD GAN，调查生成敌对网络的训练和性能。作为我们的主要理论贡献，我们通过近期工作提出的GAN损失函数中的偏差来澄清情况：我们表明MMD GANs和Wasserstein GANs的优化过程中使用的梯度估计量是无偏的，而发电机理论损耗的梯度是有偏差的在这两种情况下。我们讨论MMD批评者的核心选择问题，并且描述与Cram'AN GAN批评者使用的能量距离相对应的核心。作为一个完整的概率指标，MMD受益于最近为Wasserstein GAN开发的培训策略。在实验中，MMD GAN能够使用比Wasserstein GAN更小的评论者网络，从而得到具有匹配性能的更简单和更快的训练算法。我们还提出了GAN收敛的一个改进的度量，内核初始距离，并展示了如何在GAN训练过程中动态调整学习速率。

##### URL
[https://arxiv.org/abs/1801.01401](https://arxiv.org/abs/1801.01401)

##### PDF
[https://arxiv.org/pdf/1801.01401](https://arxiv.org/pdf/1801.01401)

