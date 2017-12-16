---
layout: post
title: "Harmonic Networks: Deep Translation and Rotation Equivariance"
date: 2017-04-11 13:34:17
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Daniel E. Worrall, Stephan J. Garbin, Daniyar Turmukhambetov, Gabriel J. Brostow
mathjax: true
---

* content
{:toc}

##### Abstract
Translating or rotating an input image should not affect the results of many computer vision tasks. Convolutional neural networks (CNNs) are already translation equivariant: input image translations produce proportionate feature map translations. This is not the case for rotations. Global rotation equivariance is typically sought through data augmentation, but patch-wise equivariance is more difficult. We present Harmonic Networks or H-Nets, a CNN exhibiting equivariance to patch-wise translation and 360-rotation. We achieve this by replacing regular CNN filters with circular harmonics, returning a maximal response and orientation for every receptive field patch. H-Nets use a rich, parameter-efficient and low computational complexity representation, and we show that deep feature maps within the network encode complicated rotational invariants. We demonstrate that our layers are general enough to be used in conjunction with the latest architectures and techniques, such as deep supervision and batch normalization. We also achieve state-of-the-art classification on rotated-MNIST, and competitive results on other benchmark challenges.

##### Abstract (translated by Google)
翻译或旋转输入图像不应影响许多计算机视觉任务的结果。卷积神经网络（CNN）已经是翻译等变体：输入图像翻译产生成比例的特征映射翻译。旋转的情况并非如此。全球旋转等变性通常是通过数据增强来寻求的，但是补丁方式的等变性更困难。我们提供Harmonic Networks或H-Nets，这是一个CNN展现平等的补丁翻译和360度旋转。我们通过用圆谐波取代常规CNN滤波器来实现这一点，为每个接收场补偿返回最大响应和方向。 H-Nets使用丰富，参数有效和低计算复杂性表示，并且我们展示网络内的深特征映射编码复杂的旋转不变量。我们证明我们的图层通用性足以与最新的体系结构和技术结合使用，如深度监视和批量标准化。我们也对旋转式MNIST进行了最先进的分类，并在其他基准挑战方面取得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1612.04642](https://arxiv.org/abs/1612.04642)

##### PDF
[https://arxiv.org/pdf/1612.04642](https://arxiv.org/pdf/1612.04642)

