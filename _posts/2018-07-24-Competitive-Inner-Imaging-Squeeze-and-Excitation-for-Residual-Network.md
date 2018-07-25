---
layout: post
title: "Competitive Inner-Imaging Squeeze and Excitation for Residual Network"
date: 2018-07-24 06:13:25
categories: arXiv_AI
tags: arXiv_AI Attention CNN Relation
author: Yang Hu, Guihua Wen, Mingnan Luo, Dan Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Residual Network make the very deep convolutional architecture works well, which use the residual unit to supplement the identity mappings. On the other hand, Squeeze-Excitation (SE) network propose a adaptively recalibrates channel-wise attention approach to model the relationship of feature maps from different convolutional channel. In this work, we propose the competitive SE mechanism for residual network, rescaling value for each channel in this structure will be determined by residual and identity mappings jointly, this design enables us to expand the meaning of channel relationship modeling in residual blocks: the modeling of competition between residual and identity mappings make identity flow can controll the complement of residual feature maps for itself. Further, we design a novel pair-view competitive SE block to shrink the consumption and re-image the global characterizations of intermediate convolutional channels. We carried out experiments on datasets: CIFAR, SVHN, ImageNet, the proposed method can be compare with the state-of-the-art results.

##### Abstract (translated by Google)
残余网络使得非常深的卷积架构运行良好，它使用剩余单元来补充身份映射。另一方面，挤压 - 激励（SE）网络提出自适应地重新校准信道方式注意方法以模拟来自不同卷积信道的特征图的关系。在这项工作中，我们提出了残余网络的竞争SE机制，该结构中每个信道的重新缩放值将由残差和身份映射联合确定，这种设计使我们能够扩展残差块中信道关系建模的含义：建模残差和身份映射之间的竞争使得身份流可以控制自身残差特征映射的补充。此外，我们设计了一种新颖的视图竞争SE模块，以缩小消耗并重新成像中间卷积通道的全局特征。我们在数据集上进行了实验：CIFAR，SVHN，ImageNet，所提出的方法可以与最先进的结果进行比较。

##### URL
[https://arxiv.org/abs/1807.08920](https://arxiv.org/abs/1807.08920)

##### PDF
[https://arxiv.org/pdf/1807.08920](https://arxiv.org/pdf/1807.08920)

