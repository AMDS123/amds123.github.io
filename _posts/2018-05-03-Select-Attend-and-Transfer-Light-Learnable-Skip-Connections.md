---
layout: post
title: "Select, Attend, and Transfer: Light, Learnable Skip Connections"
date: 2018-05-03 00:15:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Saeid Asgari Taghanaki, Aicha Bentaieb, Anmol Sharma, S. Kevin Zhou, Yefeng Zheng, Bogdan Georgescu, Puneet Sharma, Sasa Grbic, Zhoubing Xu, Dorin Comaniciu, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
Skip connections in deep networks have improved both segmentation and classification performance by facilitating the training of deeper network architectures, and reducing the risks for vanishing gradients. They equip encoder-decoder-like networks with richer feature representations, but at the cost of higher memory usage, computation, and possibly resulting in transferring non-discriminative feature maps. In this paper, we focus on improving skip connections used in segmentation networks (e.g., U-Net, V-Net, and The One Hundred Layers Tiramisu (DensNet) architectures). We propose light, learnable skip connections which learn to first select the most discriminative channels and then attend to the most discriminative regions of the selected feature maps. The output of the proposed skip connections is a unique feature map which not only reduces the memory usage and network parameters to a high extent, but also improves segmentation accuracy. We evaluate the proposed method on three different 2D and volumetric datasets and demonstrate that the proposed light, learnable skip connections can outperform the traditional heavy skip connections in terms of segmentation accuracy, memory usage, and number of network parameters.

##### Abstract (translated by Google)
深度网络中的跳过连接通过促进深层网络体系结构的培训并降低消失梯度的风险来改善分段和分类性能。它们为类似编码解码器的网络提供更丰富的特征表示，但代价是更高的内存使用量和计算量，并可能导致传输无差别的特征映射。在本文中，我们将重点放在改善分段网络（例如，U-Net，V-Net和The One Hundred Layers Tiramisu（DensNet）体系结构）中使用的跳过连接。我们提出轻松，可学习的跳过连接，学会先选择最具有歧视性的频道，然后参加所选特征地图中最具区分性的区域。所提出的跳过连接的输出是独特的特征映射，其不仅在很大程度上降低了存储器使用和网络参数，而且提高了分割准确性。我们在三个不同的二维和体积数据集上评估所提出的方法，并且证明了所提出的光可学习跳过连接在分割准确性，存储器使用和网络参数数方面可以胜过传统的大量跳过连接。

##### URL
[http://arxiv.org/abs/1804.05181](http://arxiv.org/abs/1804.05181)

##### PDF
[http://arxiv.org/pdf/1804.05181](http://arxiv.org/pdf/1804.05181)

