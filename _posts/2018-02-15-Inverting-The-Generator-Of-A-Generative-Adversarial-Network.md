---
layout: post
title: "Inverting The Generator Of A Generative Adversarial Network"
date: 2018-02-15 18:50:20
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Quantitative
author: Antonia Creswell, Anil A Bharath
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) learn a deep generative model that is able to synthesise novel, high-dimensional data samples. New data samples are synthesised by passing latent samples, drawn from a chosen prior distribution, through the generative model. Once trained, the latent space exhibits interesting properties, that may be useful for down stream tasks such as classification or retrieval. Unfortunately, GANs do not offer an "inverse model", a mapping from data space back to latent space, making it difficult to infer a latent representation for a given data sample. In this paper, we introduce a technique, inversion, to project data samples, specifically images, to the latent space using a pre-trained GAN. Using our proposed inversion technique, we are able to identify which attributes of a dataset a trained GAN is able to model and quantify GAN performance, based on a reconstruction loss. We demonstrate how our proposed inversion technique may be used to quantitatively compare performance of various GAN models trained on three image datasets. We provide code for all of our experiments, this https URL

##### Abstract (translated by Google)
生成对抗网络（GAN）学习一种能够合成新颖高维数据样本的深层生成模型。新的数据样本是通过将潜在样本从选定的先前分布中通过生成模型传递而合成的。一旦训练完成，潜在空间展现出有趣的属性，对于下游任务（如分类或检索）可能有用。不幸的是，GAN不提供“逆模型”，即从数据空间到潜在空间的映射，使得难以推断给定数据样本的潜在表示。在本文中，我们介绍了一种反演技术，使用预先训练好的GAN将数据样本，特别是图像投影到潜在空间。使用我们提出的反演技术，我们能够识别训练后的GAN能够基于重建损失对GAN性能进行建模和量化的数据集的哪些属性。我们证明了我们提出的反演技术如何可以用来定量比较在三个图像数据集上训练的各种GAN模型的性能。我们为我们所有的实验提供了代码，这个https URL

##### URL
[https://arxiv.org/abs/1802.05701](https://arxiv.org/abs/1802.05701)

##### PDF
[https://arxiv.org/pdf/1802.05701](https://arxiv.org/pdf/1802.05701)

