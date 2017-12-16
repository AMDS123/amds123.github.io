---
layout: post
title: "Deep Quantization: Encoding Convolutional Activations with Deep Generative Model"
date: 2016-11-29 06:07:28
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Image_Classification Inference Classification Recognition
author: Zhaofan Qiu, Ting Yao, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have proven highly effective for visual recognition, where learning a universal representation from activations of convolutional layer plays a fundamental problem. In this paper, we present Fisher Vector encoding with Variational Auto-Encoder (FV-VAE), a novel deep architecture that quantizes the local activations of convolutional layer in a deep generative model, by training them in an end-to-end manner. To incorporate FV encoding strategy into deep generative models, we introduce Variational Auto-Encoder model, which steers a variational inference and learning in a neural network which can be straightforwardly optimized using standard stochastic gradient method. Different from the FV characterized by conventional generative models (e.g., Gaussian Mixture Model) which parsimoniously fit a discrete mixture model to data distribution, the proposed FV-VAE is more flexible to represent the natural property of data for better generalization. Extensive experiments are conducted on three public datasets, i.e., UCF101, ActivityNet, and CUB-200-2011 in the context of video action recognition and fine-grained image classification, respectively. Superior results are reported when compared to state-of-the-art representations. Most remarkably, our proposed FV-VAE achieves to-date the best published accuracy of 94.2% on UCF101.

##### Abstract (translated by Google)
深卷积神经网络（CNNs）已经被证明对于视觉识别非常有效，其中从卷积层的激活学习通用表示形式是一个基本问题。在本文中，我们介绍了费希尔向量编码与变分自动编码器（FV-VAE），一种新的深层架构，通过对它们进行端到端的训练来量化深度生成模型中的卷积层的本地激活。为了将FV编码策略引入到深度生成模型中，我们引入了变分自动编码器模型，该模型在神经网络中进行变分推理和学习，可以使用标准随机梯度法直接优化。与传统的生成模型（例如高斯混合模型）所特有的FV不同，该模型简洁地将离散混合模型拟合到数据分布上，所提出的FV-VAE更为灵活地表示数据的自然属性以更好地推广。在视频动作识别和细粒度图像分类的背景下，对三个公共数据集UCF101，ActivityNet和CUB-200-2011进行了大量的实验。与最先进的表示法相比，报告的结果优越。最值得注意的是，我们提出的FV-VAE在UCF101上实现了最新的94.2％的最佳发布精度。

##### URL
[https://arxiv.org/abs/1611.09502](https://arxiv.org/abs/1611.09502)

##### PDF
[https://arxiv.org/pdf/1611.09502](https://arxiv.org/pdf/1611.09502)

