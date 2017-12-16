---
layout: post
title: "Progressively Diffused Networks for Semantic Image Segmentation"
date: 2017-02-20 02:34:26
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation RNN
author: Ruimao Zhang, Wei Yang, Zhanglin Peng, Xiaogang Wang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces Progressively Diffused Networks (PDNs) for unifying multi-scale context modeling with deep feature learning, by taking semantic image segmentation as an exemplar application. Prior neural networks, such as ResNet, tend to enhance representational power by increasing the depth of architectures and driving the training objective across layers. However, we argue that spatial dependencies in different layers, which generally represent the rich contexts among data elements, are also critical to building deep and discriminative representations. To this end, our PDNs enables to progressively broadcast information over the learned feature maps by inserting a stack of information diffusion layers, each of which exploits multi-dimensional convolutional LSTMs (Long-Short-Term Memory Structures). In each LSTM unit, a special type of atrous filters are designed to capture the short range and long range dependencies from various neighbors to a certain site of the feature map and pass the accumulated information to the next layer. From the extensive experiments on semantic image segmentation benchmarks (e.g., ImageNet Parsing, PASCAL VOC2012 and PASCAL-Part), our framework demonstrates the effectiveness to substantially improve the performances over the popular existing neural network models, and achieves state-of-the-art on ImageNet Parsing for large scale semantic segmentation.

##### Abstract (translated by Google)
本文介绍了渐进式扩散网络（PDN），将多尺度上下文建模与深度特征学习相结合，将语义图像分割作为示例应用。像ResNet这样的先前的神经网络倾向于通过增加体系结构的深度和跨层次的训练目标来提高代表能力。然而，我们认为，不同层次的空间依赖通常代表了数据元素之间丰富的背景，对于构建深刻而有区别的表示也是至关重要的。为此，我们的PDN能够通过插入一堆信息扩散层来逐步地在所学习的特征映射上广播信息，所述信息扩散层中的每一个利用多维卷积LSTM（长 - 短期存储器结构）。在每个LSTM单元中，设计了一种特殊类型的有害过滤器，用于从各个邻居到特征地图的特定位置捕获短距离和长距离依赖性，并将积累的信息传递到下一层。从广泛的语义图像分割基准实验（例如，ImageNet解析，PASCAL VOC2012和PASCAL-Part）中，我们的框架证明了大大改善现有神经网络模型的性能的有效性，并实现了最先进的用于大规模语义分割的ImageNet解析。

##### URL
[https://arxiv.org/abs/1702.05839](https://arxiv.org/abs/1702.05839)

##### PDF
[https://arxiv.org/pdf/1702.05839](https://arxiv.org/pdf/1702.05839)

