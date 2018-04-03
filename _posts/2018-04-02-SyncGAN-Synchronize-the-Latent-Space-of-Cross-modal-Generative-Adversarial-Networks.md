---
layout: post
title: "SyncGAN: Synchronize the Latent Space of Cross-modal Generative Adversarial Networks"
date: 2018-04-02 06:27:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Wen-Cheng Chen, Chien-Wen Chen, Min-Chun Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial network (GAN) has achieved impressive success on cross-domain generation, but it faces difficulty in cross-modal generation due to the lack of a common distribution between heterogeneous data. Most existing methods of conditional based cross-modal GANs adopt the strategy of one-directional transfer and have achieved preliminary success on text-to-image transfer. Instead of learning the transfer between different modalities, we aim to learn a synchronous latent space representing the cross-modal common concept. A novel network component named synchronizer is proposed in this work to judge whether the paired data is synchronous/corresponding or not, which can constrain the latent space of generators in the GANs. Our GAN model, named as SyncGAN, can successfully generate synchronous data (e.g., a pair of image and sound) from identical random noise. For transforming data from one modality to another, we recover the latent code by inverting the mappings of a generator and use it to generate data of different modality. In addition, the proposed model can achieve semi-supervised learning, which makes our model more flexible for practical applications.

##### Abstract (translated by Google)
生成对抗网络（GAN）在跨域生成方面取得了令人瞩目的成功，但由于异构数据之间缺乏共同分布，所以它在跨模式生成中面临困难。大多数现有的基于条件的跨模态GAN的方法采用单向传输策略，并且在文本到图像传输方面取得初步成功。我们不是学习不同形式之间的转换，而是学习表示跨模态共同概念的同步潜在空间。本文提出了一种新型的网络组件 - 同步器，用于判断配对数据是否是同步/对应的，可以约束GAN中发生器的潜在空间。我们的名为SyncGAN的GAN模型可以从相同的随机噪声中成功生成同步数据（例如，一对图像和声音）。为了将数据从一种模式转换为另一种模式，我们通过反转生成器的映射来恢复潜在的代码，并使用它来生成不同形式的数据。此外，所提出的模型可以实现半监督学习，这使得我们的模型在实际应用中更加灵活。

##### URL
[http://arxiv.org/abs/1804.00410](http://arxiv.org/abs/1804.00410)

##### PDF
[http://arxiv.org/pdf/1804.00410](http://arxiv.org/pdf/1804.00410)

