---
layout: post
title: "Parallel Separable 3D Convolution for Video and Volumetric Data Understanding"
date: 2018-09-11 18:15:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Action_Recognition Deep_Learning Recognition
author: Felix Gonda, Donglai Wei, Toufiq Parag, Hanspeter Pfister
mathjax: true
---

* content
{:toc}

##### Abstract
For video and volumetric data understanding, 3D convolution layers are widely used in deep learning, however, at the cost of increasing computation and training time. Recent works seek to replace the 3D convolution layer with convolution blocks, e.g. structured combinations of 2D and 1D convolution layers. In this paper, we propose a novel convolution block, Parallel Separable 3D Convolution (PmSCn), which applies m parallel streams of n 2D and one 1D convolution layers along different dimensions. We first mathematically justify the need of parallel streams (Pm) to replace a single 3D convolution layer through tensor decomposition. Then we jointly replace consecutive 3D convolution layers, common in modern network architectures, with the multiple 2D convolution layers (Cn). Lastly, we empirically show that PmSCn is applicable to different backbone architectures, such as ResNet, DenseNet, and UNet, for different applications, such as video action recognition, MRI brain segmentation, and electron microscopy segmentation. In all three applications, we replace the 3D convolution layers in state-of-the art models with PmSCn and achieve around 14% improvement in test performance and 40% reduction in model size and on average.

##### Abstract (translated by Google)
对于视频和体积数据理解，3D卷积层广泛用于深度学习，但是以增加计算和训练时间为代价。最近的工作寻求用卷积块替换3D卷积层，例如， 2D和1D卷积层的结构化组合。在本文中，我们提出了一种新颖的卷积块，即平行可分离3D卷积（PmSCn），它沿着不同的维度应用了n个2D和一个1D卷积层的m个并行流。我们首先在数学上证明并行流（Pm）需要通过张量分解来替换单个3D卷积层。然后，我们用多个2D卷积层（Cn）联合替换现代网络架构中常见的连续3D卷积层。最后，我们凭经验证明PmSCn适用于不同的骨干架构，如ResNet，DenseNet和UNet，适用于不同的应用，如视频动作识别，MRI脑分割和电子显微镜分割。在所有这三个应用中，我们用PmSCn替换了最先进模型中的3D卷积层，测试性能提高了约14％，平均模型尺寸减少了40％。

##### URL
[http://arxiv.org/abs/1809.04096](http://arxiv.org/abs/1809.04096)

##### PDF
[http://arxiv.org/pdf/1809.04096](http://arxiv.org/pdf/1809.04096)

