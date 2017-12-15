---
layout: post
title: "Design of Efficient Convolutional Layers using Single Intra-channel Convolution, Topological Subdivisioning and Spatial 'Bottleneck' Structure"
date: 2017-01-24 12:26:19
categories: arXiv_CV
tags: arXiv_CV CNN Relation Recognition
author: Min Wang, Baoyuan Liu, Hassan Foroosh
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks achieve remarkable visual recognition performance, at the cost of high computational complexity. In this paper, we have a new design of efficient convolutional layers based on three schemes. The 3D convolution operation in a convolutional layer can be considered as performing spatial convolution in each channel and linear projection across channels simultaneously. By unravelling them and arranging the spatial convolution sequentially, the proposed layer is composed of a single intra-channel convolution, of which the computation is negligible, and a linear channel projection. A topological subdivisioning is adopted to reduce the connection between the input channels and output channels. Additionally, we also introduce a spatial "bottleneck" structure that utilizes a convolution-projection-deconvolution pipeline to take advantage of the correlation between adjacent pixels in the input. Our experiments demonstrate that the proposed layers remarkably outperform the standard convolutional layers with regard to accuracy/complexity ratio. Our models achieve similar accuracy to VGG, ResNet-50, ResNet-101 while requiring 42, 4.5, 6.5 times less computation respectively.

##### Abstract (translated by Google)
深卷积神经网络以高计算复杂度为代价实现卓越的视觉识别性能。在本文中，我们有一个基于三种方案的高效卷积层的新设计。卷积层中的3D卷积运算可以被认为是在每个通道中执行空间卷积，并且同时执行跨通道的线性投影。通过分解它们并按顺序排列空间卷积，所提出的层由单个通道内卷积组成，其中计算可忽略不计，并且是线性通道投影。采用拓扑细分来减少输入通道和输出通道之间的连接。此外，我们还引入了空间“瓶颈”结构，利用卷积 - 投影 - 反卷积管道来利用输入中相邻像素之间的相关性。我们的实验表明，所提出的层在精度/复杂度比方面明显优于标准卷积层。我们的模型达到与VGG，ResNet-50，ResNet-101类似的精度，同时分别需要42,4.5,6.5倍的计算。

##### URL
[https://arxiv.org/abs/1608.04337](https://arxiv.org/abs/1608.04337)

##### PDF
[https://arxiv.org/pdf/1608.04337](https://arxiv.org/pdf/1608.04337)

