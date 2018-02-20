---
layout: post
title: "Differentially Private Generative Adversarial Network"
date: 2018-02-19 18:05:33
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Liyang Xie, Kaixiang Lin, Shu Wang, Fei Wang, Jiayu Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Network (GAN) and its variants have recently attracted intensive research interests due to their elegant theoretical foundation and excellent empirical performance as generative models. These tools provide a promising direction in the studies where data availability is limited. One common issue in GANs is that the density of the learned generative distribution could concentrate on the training data points, meaning that they can easily remember training samples due to the high model complexity of deep networks. This becomes a major concern when GANs are applied to private or sensitive data such as patient medical records, and the concentration of distribution may divulge critical patient information. To address this issue, in this paper we propose a differentially private GAN (DPGAN) model, in which we achieve differential privacy in GANs by adding carefully designed noise to gradients during the learning procedure. We provide rigorous proof for the privacy guarantee, as well as comprehensive empirical evidence to support our analysis, where we demonstrate that our method can generate high quality data points at a reasonable privacy level.

##### Abstract (translated by Google)
生成对抗网络（GAN）及其变体最近因其优雅的理论基础和优秀的实证性表现作为生成模型而引起了广泛的研究兴趣。这些工具为数据可用性有限的研究提供了有希望的方向。 GAN中的一个常见问题是学习生成分布的密度可能集中在训练数据点上，这意味着由于深度网络的高模型复杂性，他们可以轻松记住训练样本。当GAN应用于私人或敏感数据（如患者病历）时，这成为一个主要问题，并且分发的集中可能会泄漏关键的患者信息。为了解决这个问题，在本文中，我们提出了一种差分私有GAN（DPGAN）模型，在该模型中，我们通过在学习过程中为设计噪声添加了精心设计的噪声来实现GAN中的差分隐私。我们为隐私保证提供了严格的证据，并提供了全面的经验证据来支持我们的分析，我们证明了我们的方法可以在合理的隐私级别生成高质量的数据点。

##### URL
[http://arxiv.org/abs/1802.06739](http://arxiv.org/abs/1802.06739)

##### PDF
[http://arxiv.org/pdf/1802.06739](http://arxiv.org/pdf/1802.06739)

