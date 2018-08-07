---
layout: post
title: "Non-locally Enhanced Encoder-Decoder Network for Single Image De-raining"
date: 2018-08-04 15:09:01
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation
author: Guanbin Li, Xiang He, Wei Zhang, Huiyou Chang, Le Dong, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Single image rain streaks removal has recently witnessed substantial progress due to the development of deep convolutional neural networks. However, existing deep learning based methods either focus on the entrance and exit of the network by decomposing the input image into high and low frequency information and employing residual learning to reduce the mapping range, or focus on the introduction of cascaded learning scheme to decompose the task of rain streaks removal into multi-stages. These methods treat the convolutional neural network as an encapsulated end-to-end mapping module without deepening into the rationality and superiority of neural network design. In this paper, we delve into an effective end-to-end neural network structure for stronger feature expression and spatial correlation learning. Specifically, we propose a non-locally enhanced encoder-decoder network framework, which consists of a pooling indices embedded encoder-decoder network to efficiently learn increasingly abstract feature representation for more accurate rain streaks modeling while perfectly preserving the image detail. The proposed encoder-decoder framework is composed of a series of non-locally enhanced dense blocks that are designed to not only fully exploit hierarchical features from all the convolutional layers but also well capture the long-distance dependencies and structural information. Extensive experiments on synthetic and real datasets demonstrate that the proposed method can effectively remove rain-streaks on rainy image of various densities while well preserving the image details, which achieves significant improvements over the recent state-of-the-art methods.

##### Abstract (translated by Google)
由于深度卷积神经网络的发展，单图像雨条去除最近已经取得了实质性进展。然而，现有的基于深度学习的方法或者通过将输入图像分解成高频和低频信息并且使用残差学习来减少映射范围来关注网络的进入和退出，或者集中于引入级联学习方案来分解将雨条划分为多个阶段的任务。这些方法将卷积神经网络视为封装的端到端映射模块，而不深入神经网络设计的合理性和优越性。在本文中，我们深入研究了一种有效的端到端神经网络结构，用于更强的特征表达和空间相关学习。具体来说，我们提出了一种非局部增强的编码器 - 解码器网络框架，它由嵌入式索引编码器 - 解码器网络组成，有效地学习越来越抽象的特征表示，以便更精确地进行雨条纹建模，同时完美地保留图像细节。所提出的编码器 - 解码器框架由一系列非局部增强的密集块组成，这些块不仅可以完全利用来自所有卷积层的分层特征，而且可以很好地捕获长距离依赖性和结构信息。对合成和真实数据集的大量实验表明，所提出的方法可以有效地去除各种密度的雨天图像上的雨条纹，同时很好地保留图像细节，与最近的最新方法相比实现了显着的改进。

##### URL
[https://arxiv.org/abs/1808.01491](https://arxiv.org/abs/1808.01491)

##### PDF
[https://arxiv.org/pdf/1808.01491](https://arxiv.org/pdf/1808.01491)

