---
layout: post
title: "Improved Training of Wasserstein GANs"
date: 2017-05-29 17:52:41
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Language_Model
author: Ishaan Gulrajani, Faruk Ahmed, Martin Arjovsky, Vincent Dumoulin, Aaron Courville
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) are powerful generative models, but suffer from training instability. The recently proposed Wasserstein GAN (WGAN) makes progress toward stable training of GANs, but can still generate low-quality samples or fail to converge in some settings. We find that these problems are often due to the use of weight clipping in WGAN to enforce a Lipschitz constraint on the critic, which can lead to pathological behavior. We propose an alternative to clipping weights: penalize the norm of gradient of the critic with respect to its input. Our proposed method performs better than standard WGAN and enables stable training of a wide variety of GAN architectures with almost no hyperparameter tuning, including 101-layer ResNets and language models over discrete data. We also achieve high quality generations on CIFAR-10 and LSUN bedrooms.

##### Abstract (translated by Google)
生成对抗网络（GAN）是强大的生成模型，但是受到训练不稳定的困扰。最近提出的Wasserstein GAN（WGAN）在GAN的稳定训练方面取得了进展，但是仍然可以产生低质量的样本，或者在某些情况下不能收敛。我们发现这些问题通常是由于在WGAN中使用权重限制来对批评者施加Lipschitz约束，这可能导致病态行为。我们提出了一个替代权重的方法：惩罚批评者关于其投入的梯度的规范。我们提出的方法比标准的WGAN执行得更好，能够稳定地培训各种GAN体系结构，几乎不需要超参数调整，包括101层ResNet和离散数据上的语言模型。我们还在CIFAR-10和LSUN卧室中实现了高品质的生产。

##### URL
[https://arxiv.org/abs/1704.00028](https://arxiv.org/abs/1704.00028)

##### PDF
[https://arxiv.org/pdf/1704.00028](https://arxiv.org/pdf/1704.00028)

