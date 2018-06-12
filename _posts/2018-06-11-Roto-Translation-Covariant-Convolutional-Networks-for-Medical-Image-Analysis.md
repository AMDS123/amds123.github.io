---
layout: post
title: "Roto-Translation Covariant Convolutional Networks for Medical Image Analysis"
date: 2018-06-11 17:53:31
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Erik J Bekkers, Maxime W Lafarge, Mitko Veta, Koen AJ Eppenhof, Josien PW Pluim, Remco Duits
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework for rotation and translation covariant deep learning using $SE(2)$ group convolutions. The group product of the special Euclidean motion group $SE(2)$ describes how a concatenation of two roto-translations results in a net roto-translation. We encode this geometric structure into convolutional neural networks (CNNs) via $SE(2)$ group convolutional layers, which fit into the standard 2D CNN framework, and which allow to generically deal with rotated input samples without the need for data augmentation. 
 We introduce three layers: a lifting layer which lifts a 2D (vector valued) image to an $SE(2)$-image, i.e., 3D (vector valued) data whose domain is $SE(2)$; a group convolution layer from and to an $SE(2)$-image; and a projection layer from an $SE(2)$-image to a 2D image. The lifting and group convolution layers are $SE(2)$ covariant (the output roto-translates with the input). The final projection layer, a maximum intensity projection over rotations, makes the full CNN rotation invariant. 
 We show with three different problems in histopathology, retinal imaging, and electron microscopy that with the proposed group CNNs, state-of-the-art performance can be achieved, without the need for data augmentation by rotation and with increased performance compared to standard CNNs that do rely on augmentation.

##### Abstract (translated by Google)
我们提出了一个使用$ SE（2）$ group卷积的旋转和平移协变深度学习框架。特殊的欧几里德运动组$ SE（2）$的组乘积描述了两个旋转翻译的连接如何产生一个净旋转翻译。我们通过$ SE（2）$组卷积层将这种几何结构编码为卷积神经网络（CNN），这些卷积层符合标准2D CNN框架，并且允许一般处理旋转输入样本而不需要数据增强。
 我们介绍三层：一个将2D（矢量值）图像提升为$ SE（2）$  - 图像的升降层，即其域为$ SE（2）$的3D（矢量值）数据;来自和到达$ SE（2）$  - 图像的组卷积层;以及从$ SE（2）$  - 图像到2D图像的投影层。提升和组卷积层是$ SE（2）$ covariant（输出roto  - 随输入转换）。最后的投影层，旋转的最大强度投影，使得整个CNN旋转不变。
 我们展示了组织病理学，视网膜成像和电子显微镜中的三个不同问题，与提出的组CNN相比，可以实现最先进的性能，而不需要通过旋转进行数据增强并且与标准CNN相比具有提高的性能那依赖于增强。

##### URL
[http://arxiv.org/abs/1804.03393](http://arxiv.org/abs/1804.03393)

##### PDF
[http://arxiv.org/pdf/1804.03393](http://arxiv.org/pdf/1804.03393)

