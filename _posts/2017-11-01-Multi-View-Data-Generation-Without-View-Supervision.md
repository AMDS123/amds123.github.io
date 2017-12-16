---
layout: post
title: "Multi-View Data Generation Without View Supervision"
date: 2017-11-01 12:18:26
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Mickaël Chen, Ludovic Denoyer, Thierry Artières
mathjax: true
---

* content
{:toc}

##### Abstract
The development of high-dimensional generative models has recently gained a great surge of interest with the introduction of variational auto-encoders and generative adversarial neural networks. Different variants have been proposed where the underlying latent space is structured, for example, based on attributes describing the data to generate. We focus on a particular problem where one aims at generating samples corresponding to a number of objects under various views. We assume that the distribution of the data is driven by two independent latent factors: the content, which represents the intrinsic features of an object, and the view, which stands for the settings of a particular observation of that object. Therefore, we propose a generative model and a conditional variant built on such a disentangled latent space. This approach allows us to generate realistic samples corresponding to various objects in a high variety of views. Unlike many multi-view approaches, our model doesn't need any supervision on the views but only on the content. Compared to other conditional generation approaches that are mostly based on binary or categorical attributes, we make no such assumption about the factors of variations. Our model can be used on problems with a huge, potentially infinite, number of categories. We experiment it on four image datasets on which we demonstrate the effectiveness of the model and its ability to generalize.

##### Abstract (translated by Google)
近年来，高维生成模型的发展引起了变分自动编码器和生成对抗神经网络的兴趣。已经提出了不同的变体，其中例如基于描述要生成的数据的属性来构建潜在的空间。我们专注于一个特定的问题，其中一个目标是在不同的观点下生成对应于多个对象的样本。我们假设数据的分布是由两个独立的潜在因素驱动的：代表对象内在特征的内容和代表特定对象观察设置的视图。因此，我们提出了一个建立在这样一个解开的潜在空间上的生成模型和条件变体。这种方法使我们能够在各种各样的视图中生成对应于各种对象的逼真的样本。与许多多视角方法不同，我们的模型不需要对视图进行任何监督，而只需要对内容进行监督。与其他主要基于二元属性或分类属性的条件生成方法相比，我们对变异因素没有这样的假设。我们的模型可以用于大量可能无限多个类别的问题。我们在四个图像数据集上进行实验，在这些数据集上我们展示了该模型的有效性及其推广能力。

##### URL
[https://arxiv.org/abs/1711.00305](https://arxiv.org/abs/1711.00305)

##### PDF
[https://arxiv.org/pdf/1711.00305](https://arxiv.org/pdf/1711.00305)

