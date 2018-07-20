---
layout: post
title: "Guided Upsampling Network for Real-Time Semantic Segmentation"
date: 2018-07-19 14:40:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Quantitative
author: Davide Mazzini
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation architectures are mainly built upon an encoder-decoder structure. These models perform subsequent downsampling operations in the encoder. Since operations on high-resolution activation maps are computationally expensive, usually the decoder produces output segmentation maps by upsampling with parameters-free operators like bilinear or nearest-neighbor. We propose a Neural Network named Guided Upsampling Network which consists of a multiresolution architecture that jointly exploits high-resolution and large context information. Then we introduce a new module named Guided Upsampling Module (GUM) that enriches upsampling operators by introducing a learnable transformation for semantic maps. It can be plugged into any existing encoder-decoder architecture with little modifications and low additional computation cost. We show with quantitative and qualitative experiments how our network benefits from the use of GUM module. A comprehensive set of experiments on the publicly available Cityscapes dataset demonstrates that Guided Upsampling Network can efficiently process high-resolution images in real-time while attaining state-of-the art performances.

##### Abstract (translated by Google)
语义分段架构主要基于编码器 - 解码器结构。这些模型在编码器中执行后续的下采样操作。由于在高分辨率激活图上的操作在计算上是昂贵的，因此通常解码器通过使用诸如双线性或最近邻居的无参数运算符的上采样来产生输出分段图。我们提出了一种名为Guided Upsampling Network的神经网络，它由多分辨率体系结构组成，它共同利用高分辨率和大的上下文信息。然后我们引入一个名为Guided Upsampling Module（GUM）的新模块，通过引入语义映射的可学习转换来丰富上采样运算符。它可以插入任何现有的编码器 - 解码器架构，只需很少的修改和较低的额外计算成本。我们通过定量和定性实验展示了我们的网络如何从使用GUM模块中受益。对公开可用的Cityscapes数据集进行的一系列全面实验表明，Guided Upsampling Network可以实现高效分辨率图像的实时处理，同时获得最先进的性能。

##### URL
[https://arxiv.org/abs/1807.07466](https://arxiv.org/abs/1807.07466)

##### PDF
[https://arxiv.org/pdf/1807.07466](https://arxiv.org/pdf/1807.07466)

