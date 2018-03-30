---
layout: post
title: "Removing scanner biases using Generative Adversarial Networks"
date: 2018-03-26 00:49:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Deep_Learning
author: Harrison Nguyen, Richard W. Morris, Anthony W. Harris, Mayuresh S. Korgoankar, Fabio Ramos
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic Resonance Imaging (MRI) of the brain has been used to investigate a wide range of neurological disorders, but data acquisition can be expensive, time-consuming, and inconvenient. Multi-site studies present a valuable opportunity to advance research by pooling data in order to increase sensitivity and statistical power. However images derived from MRI are susceptible to both obvious and non-obvious differences between sites which can introduce bias and subject variance, and so reduce statistical power. To rectify these differences, we propose a data driven approach using a deep learning architecture known as generative adversarial networks (GANs). GANs learn to estimate two distributions, and can then be used to transform examples from one distribution into the other distribution. Here we transform T1-weighted brain images collected from two different sites into MR images from the same site. We evaluate whether our model can reduce site-specific differences without loss of information related to gender (male, female) or clinical diagnosis (schizophrenia, bipolar disorder, healthy). When trained appropriately, our model is able to normalise imaging sets to a common scanner set with less information loss compared to current approaches. An important advantage is our method can be treated as a black box that does not require any knowledge of the sources of bias but only needs at least two distinct imaging sets.

##### Abstract (translated by Google)
大脑的磁共振成像（MRI）已被用于研究各种神经疾病，但是数据采集可能是昂贵的，耗时的和不方便的。多点研究提供了一个宝贵的机会，通过汇总数据来提高研究水平，从而提高敏感性和统计效能。然而，来源于MRI的图像对于可能引入偏倚和受试者变异的站点之间的明显和非明显差异是敏感的，因此降低统计效能。为了纠正这些差异，我们提出了一种使用被称为生成对抗网络（GAN）的深度学习架构的数据驱动方法。 GAN学会估计两个分布，然后可以用来将一个分布的例子转换成另一个分布。在这里，我们将从两个不同部位采集的T1加权脑图像转换为来自同一站点的MR图像。我们评估我们的模型是否可以减少位点特异性差异而不丧失有关性别（男性，女性）或临床诊断（精神分裂症，双相性精神障碍，健康）的信息。经过适当的训练后，我们的模型能够将成像设备归一化为普通的扫描仪组，与目前的方法相比，信息丢失较少。一个重要的优点是我们的方法可以被视为一个黑盒子，它不需要任何偏见源的知识，但只需要至少两个不同的成像集。

##### URL
[https://arxiv.org/abs/1803.09375](https://arxiv.org/abs/1803.09375)

##### PDF
[https://arxiv.org/pdf/1803.09375](https://arxiv.org/pdf/1803.09375)

