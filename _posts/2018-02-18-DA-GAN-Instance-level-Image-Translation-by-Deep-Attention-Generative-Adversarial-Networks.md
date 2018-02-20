---
layout: post
title: "DA-GAN: Instance-level Image Translation by Deep Attention Generative Adversarial Networks"
date: 2018-02-18 22:16:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN
author: Shuang Ma, Jianlong Fu, Chang Wen Chen, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised image translation, which aims in translating two independent sets of images, is challenging in discovering the correct correspondences without paired data. Existing works build upon Generative Adversarial Network (GAN) such that the distribution of the translated images are indistinguishable from the distribution of the target set. However, such set-level constraints cannot learn the instance-level correspondences (e.g. aligned semantic parts in object configuration task). This limitation often results in false positives (e.g. geometric or semantic artifacts), and further leads to mode collapse problem. To address the above issues, we propose a novel framework for instance-level image translation by Deep Attention GAN (DA-GAN). Such a design enables DA-GAN to decompose the task of translating samples from two sets into translating instances in a highly-structured latent space. Specifically, we jointly learn a deep attention encoder, and the instancelevel correspondences could be consequently discovered through attending on the learned instance pairs. Therefore, the constraints could be exploited on both set-level and instance-level. Comparisons against several state-ofthe- arts demonstrate the superiority of our approach, and the broad application capability, e.g, pose morphing, data augmentation, etc., pushes the margin of domain translation problem.

##### Abstract (translated by Google)
旨在翻译两组独立图像的无监督图像翻译在发现没有配对数据的正确对应方面具有挑战性。现有的作品基于生成敌对网络（GAN），使得翻译图像的分布与目标集合的分布无法区分。然而，这样的集合级别约束不能学习实例级别的对应关系（例如对象配置任务中对齐的语义部分）。这种限制常常导致误报（例如几何或语义伪像），并进一步导致模式崩溃问题。为了解决上述问题，我们提出了一个由Deep Attention GAN（DA-GAN）提供的用于实例级图像转换的新框架。这样的设计使DA-GAN能够分解将样本从两套翻译成高度结构化的潜在空间中的翻译实例。具体来说，我们共同学习一个深入关注的编码器，通过参加学习的实例对可以发现实例级别的对应关系。因此，可以在集合级别和实例级别上利用约束条件。与几种现有技术的比较证明了我们的方法的优越性，并且广泛的应用能力，例如变形，数据增加等，推动了域翻译问题的边际。

##### URL
[http://arxiv.org/abs/1802.06454](http://arxiv.org/abs/1802.06454)

##### PDF
[http://arxiv.org/pdf/1802.06454](http://arxiv.org/pdf/1802.06454)

