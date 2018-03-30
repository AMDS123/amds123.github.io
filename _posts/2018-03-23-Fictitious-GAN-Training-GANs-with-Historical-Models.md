---
layout: post
title: "Fictitious GAN: Training GANs with Historical Models"
date: 2018-03-23 03:46:12
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hao Ge, Yin Xia, Xu Chen, Randall Berry, Ying Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are powerful tools for learning generative models. In practice, the training may suffer from lack of convergence. GANs are commonly viewed as a two-player zero-sum game between two neural networks. Here, we leverage this game theoretic view to study the convergence behavior of the training process. Inspired by the fictitious play learning process, a novel training method, referred to as Fictitious GAN, is introduced. Fictitious GAN trains the deep neural networks using a mixture of historical models. Specifically, the discriminator (resp. generator) is updated according to the best-response to the mixture outputs from a sequence of previously trained generators (resp. discriminators). It is shown that Fictitious GAN can effectively resolve some convergence issues that cannot be resolved by the standard training approach. It is proved that asymptotically the average of the generator outputs has the same distribution as the data samples.

##### Abstract (translated by Google)
生成对抗网络（GAN）是学习生成模型的强大工具。实际上，培训可能会因缺乏趋同而受到影响。 GAN通常被视为两个神经网络之间的双人零和游戏。在这里，我们利用这种博弈论的观点来研究训练过程的收敛行为。受虚拟游戏学习过程的启发，引入了一种称为Fictitious GAN的新型训练方法。虚构的GAN使用历史模型的混合来训练深度神经网络。具体地说，鉴别器（或发生器）根据对来自一系列先前训练的发生器（或鉴别器）的混合输出的最佳响应而被更新。结果表明，Fictitious GAN可以有效解决标准训练方法无法解决的一些收敛问题。证明渐近地，发生器输出的平均值与数据样本具有相同的分布。

##### URL
[https://arxiv.org/abs/1803.08647](https://arxiv.org/abs/1803.08647)

##### PDF
[https://arxiv.org/pdf/1803.08647](https://arxiv.org/pdf/1803.08647)

