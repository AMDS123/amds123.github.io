---
layout: post
title: "Face Parsing via a Fully-Convolutional Continuous CRF Neural Network"
date: 2017-08-12 01:17:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN
author: Lei Zhou, Zhi Liu, Xiangjian He
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we address the face parsing task with a Fully-Convolutional continuous CRF Neural Network (FC-CNN) architecture. In contrast to previous face parsing methods that apply region-based subnetwork hundreds of times, our FC-CNN is fully convolutional with high segmentation accuracy. To achieve this goal, FC-CNN integrates three subnetworks, a unary network, a pairwise network and a continuous Conditional Random Field (C-CRF) network into a unified framework. The high-level semantic information and low-level details across different convolutional layers are captured by the convolutional and deconvolutional structures in the unary network. The semantic edge context is learnt by the pairwise network branch to construct pixel-wise affinity. Based on a differentiable superpixel pooling layer and a differentiable C-CRF layer, the unary network and pairwise network are combined via a novel continuous CRF network to achieve spatial consistency in both training and test procedure of a deep neural network. Comprehensive evaluations on LFW-PL and HELEN datasets demonstrate that FC-CNN achieves better performance over the other state-of-arts for accurate face labeling on challenging images.

##### Abstract (translated by Google)
在这项工作中，我们使用完全卷积连续CRF神经网络（FC-CNN）体系结构来解决人脸解析任务。与先前应用基于区域的子网数百次的人脸解析方法相比，我们的FC-CNN具有高分割精度的完全卷积。为了实现这一目标，FC-CNN将一个网络，一对网络和一个连续的条件随机场（C-CRF）网络三个子网络集成到一个统一的框架中。一元网络中的卷积和去卷积结构捕获不同卷积层的高层语义信息和低层细节。语义边缘上下文由成对网络分支学习，以构建逐像素亲和度。基于可微超像素池层和可微C-CRF层，通过一个新型的连续CRF网络将一元网络和成对网络结合起来，在深度神经网络的训练和测试过程中实现空间一致性。对LFW-PL和HELEN数据集的全面评估表明，FC-CNN在具有挑战性的图像上实现了比其他现有技术更好的精确面部标记的性能。

##### URL
[https://arxiv.org/abs/1708.03736](https://arxiv.org/abs/1708.03736)

##### PDF
[https://arxiv.org/pdf/1708.03736](https://arxiv.org/pdf/1708.03736)

