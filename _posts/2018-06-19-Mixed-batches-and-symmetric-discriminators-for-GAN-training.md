---
layout: post
title: "Mixed batches and symmetric discriminators for GAN training"
date: 2018-06-19 12:39:11
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Thomas Lucas, Corentin Tallec, Jakob Verbeek, Yann Ollivier
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are pow- erful generative models based on providing feed- back to a generative network via a discriminator network. However, the discriminator usually as- sesses individual samples. This prevents the dis- criminator from accessing global distributional statistics of generated samples, and often leads to mode dropping: the generator models only part of the target distribution. We propose to feed the discriminator with mixed batches of true and fake samples, and train it to predict the ratio of true samples in the batch. The latter score does not depend on the order of samples in a batch. Rather than learning this invariance, we introduce a generic permutation-invariant discriminator ar- chitecture. This architecture is provably a uni- versal approximator of all symmetric functions. Experimentally, our approach reduces mode col- lapse in GANs on two synthetic datasets, and obtains good results on the CIFAR10 and CelebA datasets, both qualitatively and quantitatively.

##### Abstract (translated by Google)
生成对抗网络（GAN）是强大的生成模型，基于通过鉴别器网络向生成网络提供反馈。但是，鉴别器通常会对各个样本进行分类。这样可以防止分析人员访问生成的样本的全局分布统计信息，并且通常会导致模式下降：生成器仅对目标分布的一部分进行建模。我们建议将混合批次的真假样品送入鉴别器，并对其进行训练以预测批次中真实样品的比例。后者得分不取决于批次中样品的顺序。我们不是学习这种不变性，而是引入一个通用的置换不变鉴别器结构。这种体系结构可以证明是所有对称函数的一种普遍近似。实验中，我们的方法在两个合成数据集上减少了GAN中的模式损坏，并在CIFAR10和CelebA数据集上从定性和定量两方面获得了良好结果。

##### URL
[http://arxiv.org/abs/1806.07185](http://arxiv.org/abs/1806.07185)

##### PDF
[http://arxiv.org/pdf/1806.07185](http://arxiv.org/pdf/1806.07185)

