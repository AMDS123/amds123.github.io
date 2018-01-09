---
layout: post
title: "Identity-preserving Face Recovery from Portraits"
date: 2018-01-08 00:25:35
categories: arXiv_CV
tags: arXiv_CV Face Embedding
author: Fatemeh Shiri, Xin Yu, Fatih Porikli, Richard Hartley, Piotr Koniusz
mathjax: true
---

* content
{:toc}

##### Abstract
Recovering the latent photorealistic faces from their artistic portraits aids human perception and facial analysis. However, recovering photorealistic faces from stylized portraits while preserving identity is challenging because the fine details of real faces can be distorted or lost in stylized images. In this paper, we present a new Identity-preserving Face Recovery from Portraits (IFRP) method to recover latent photorealistic faces from unaligned stylized portraits. Our IFRP method consists of two components: Style Removal Network (SRN) and Discriminative Network (DN). The SRN is designed to transfer feature maps of stylized images to the feature maps of the corresponding photorealistic faces. By embedding spatial transformer networks into the SRN, our method can compensate for misalignments of stylized faces automatically and output aligned realistic face images. The DN is used to enforce recovered face images to be similar to authentic faces. To ensure the identity preservation, we promote the recovered and ground-truth faces to share similar visual features via a distance measure which compares features of recovered and ground-truth faces extracted from a pre-trained VGG network. Our approach is evaluated on a large-scale synthesized dataset of real and stylized face pairs and outperforms the state-of-the-art methods. In addition, we demonstrate that our method can also recover photorealistic faces from unseen stylized portraits (unavailable in training) as well as original paintings.

##### Abstract (translated by Google)
从他们的艺术肖像中恢复潜在的真实感人脸，有助于人类的感知和面部分析。然而，在保留身份的同时从风格化的肖像中恢复真实感的人脸是具有挑战性的，因为真实人脸的细节可能会在程式化的图像中被扭曲或丢失。在本文中，我们提出了一种新的身份保留脸部恢复（IFRP）方法，以从未对齐的风格化肖像恢复潜在的真实感人脸。我们的IFRP方法由两部分组成：风格去除网络（SRN）和判别网络（DN）。 SRN旨在将风格化图像的特征地图转换为相应真实感人脸的特征地图。通过将空间变换网络嵌入到SRN中，我们的方法可以自动补偿程序化人脸的不对齐，并输出对齐的真实人脸图像。 DN用于强制恢复的脸部图像与真实的脸部相似。为了保证身份的保存，我们通过一个距离度量来促进恢复的和地面真实面孔共享相似的视觉特征，该距离度量比较从预先训练的VGG网络中提取的恢复的和地面真实面部的特征。我们的方法是评估一个大规模的真实和风格化的脸对合成数据集，并且胜过最先进的方法。此外，我们证明我们的方法还可以从看不见的风格化肖像（训练中不可用）以及原始绘画恢复逼真的脸部。

##### URL
[http://arxiv.org/abs/1801.02279](http://arxiv.org/abs/1801.02279)

##### PDF
[http://arxiv.org/pdf/1801.02279](http://arxiv.org/pdf/1801.02279)

