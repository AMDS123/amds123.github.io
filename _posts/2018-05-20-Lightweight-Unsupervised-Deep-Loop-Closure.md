---
layout: post
title: "Lightweight Unsupervised Deep Loop Closure"
date: 2018-05-20 04:28:46
categories: arXiv_RO
tags: arXiv_RO Embedding Detection SLAM
author: Nate Merrill, Guoquan Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Robust efficient loop closure detection is essential for large-scale real-time SLAM. In this paper, we propose a novel unsupervised deep neural network architecture of a feature embedding for visual loop closure that is both reliable and compact. Our model is built upon the autoencoder architecture, tailored specifically to the problem at hand. To train our network, we inflict random noise on our input data as the denoising autoencoder does, but, instead of applying random dropout, we warp images with randomized projective transformations to emulate natural viewpoint changes due to robot motion. Moreover, we utilize the geometric information and illumination invariance provided by histogram of oriented gradients (HOG), forcing the encoder to reconstruct a HOG descriptor instead of the original image. As a result, our trained model extracts features robust to extreme variations in appearance directly from raw images, without the need for labeled training data or environment-specific training. We perform extensive experiments on various challenging datasets, showing that the proposed deep loop-closure model consistently outperforms the state-of-the-art methods in terms of effectiveness and efficiency. Our model is fast and reliable enough to close loops in real time with no dimensionality reduction, and capable of replacing generic off-the-shelf networks in state-of-the-art ConvNet-based loop closure systems.

##### Abstract (translated by Google)
对于大规模实时SLAM来说，鲁棒高效的环路闭合检测非常重要。在本文中，我们提出了一种新颖的无监督深度神经网络架构的特征嵌入视觉闭环是可靠和紧凑的。我们的模型基于autoencoder体系结构，专门针对手头的问题量身定制。为了训练我们的网络，我们在降噪自动编码器中对输入数据施加随机噪声，但是，我们不是应用随机丢失，而是使用随机投影变换来扭曲图像，以模拟由于机器人运动引起的自然视点变化。此外，我们利用定向梯度直方图（HOG）提供的几何信息和光照不变性，迫使编码器重建HOG描述符而不是原始图像。因此，我们训练有素的模型可直接从原始图像中提取强健的外观极端变化，而无需标记训练数据或特定环境的训练。我们对各种具有挑战性的数据集进行了广泛的实验，表明所提出的深闭环模型在效率和效率方面始终优于最先进的方法。我们的模型足够快速和可靠，足以实时关闭环路，无需降维，并且能够取代先进的基于ConvNet的闭环系统中的通用现成网络。

##### URL
[http://arxiv.org/abs/1805.07703](http://arxiv.org/abs/1805.07703)

##### PDF
[http://arxiv.org/pdf/1805.07703](http://arxiv.org/pdf/1805.07703)

