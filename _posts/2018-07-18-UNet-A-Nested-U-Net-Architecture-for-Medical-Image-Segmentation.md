---
layout: post
title: "UNet++: A Nested U-Net Architecture for Medical Image Segmentation"
date: 2018-07-18 04:08:21
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Zongwei Zhou, Md Mahfuzur Rahman Siddiquee, Nima Tajbakhsh, Jianming Liang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present UNet++, a new, more powerful architecture for medical image segmentation. Our architecture is essentially a deeply-supervised encoder-decoder network where the encoder and decoder sub-networks are connected through a series of nested, dense skip pathways. The re-designed skip pathways aim at reducing the semantic gap between the feature maps of the encoder and decoder sub-networks. We argue that the optimizer would deal with an easier learning task when the feature maps from the decoder and encoder networks are semantically similar. We have evaluated UNet++ in comparison with U-Net and wide U-Net architectures across multiple medical image segmentation tasks: nodule segmentation in the low-dose CT scans of chest, nuclei segmentation in the microscopy images, liver segmentation in abdominal CT scans, and polyp segmentation in colonoscopy videos. Our experiments demonstrate that UNet++ with deep supervision achieves an average IoU gain of 3.9 and 3.4 points over U-Net and wide U-Net, respectively.

##### Abstract (translated by Google)
在本文中，我们介绍了UNet ++，一种新的，更强大的医学图像分割架构。我们的架构本质上是一个深度监督的编码器 - 解码器网络，其中编码器和解码器子网络通过一系列嵌套的密集跳过路径连接。重新设计的跳过路径旨在减少编码器和解码器子网络的特征映射之间的语义差距。我们认为当来自解码器和编码器网络的特征映射在语义上相似时，优化器将处理更容易的学习任务。我们评估了UNet ++与U-Net和广泛的U-Net架构在多个医学图像分割任务中的比较：胸部低剂量CT扫描中的结节分割，显微镜图像中的细胞核分割，腹部CT扫描中的肝脏分割，以及结肠镜检查视频中的息肉分割。我们的实验表明，深度监督的UNet ++分别比U-Net和宽U-Net实现了3.9和3.4点的平均IoU增益。

##### URL
[http://arxiv.org/abs/1807.10165](http://arxiv.org/abs/1807.10165)

##### PDF
[http://arxiv.org/pdf/1807.10165](http://arxiv.org/pdf/1807.10165)

