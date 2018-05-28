---
layout: post
title: "Deep Residual Networks with a Fully Connected Recon-struction Layer for Single Image Super-Resolution"
date: 2018-05-24 14:11:19
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yongliang Tang, Weiguo Gong, Xi Chen, Zhenghao Li, Weihong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep neural networks have achieved impressive performance in terms of both reconstruction accuracy and efficiency for single image super-resolution (SISR). However, the network model of these methods is a fully convolutional neural network, which is limit to exploit contextual information over the global region of the input image. In this paper, we discuss a new SR architecture where features are extracted in the low-resolution (LR) space, and then we use a fully connected layer which learns an array of upsampling weights to reconstruct the desired high-resolution (HR) image from the final LR features. By doing so, we effectively exploit global context information over the input image region, whilst maintaining the low computational complexity for the overall SR operation. In addition, we introduce an edge difference constraint into our loss function to pre-serve edges and texture structures. Extensive experiments validate that our meth-od outperforms the existing state-of-the-art methods

##### Abstract (translated by Google)
最近，深度神经网络在单幅图像超分辨率（SISR）的重建准确性和效率方面取得了令人印象深刻的性能。然而，这些方法的网络模型是一个完全卷积神经网络，它限制了在输入图像的全局范围内利用上下文信息。在本文中，我们讨论一种新的SR架构，其中在低分辨率（LR）空间中提取特征，然后我们使用完全连接的层，学习一组上采样权重来重建所需的高分辨率（HR）图像从最终的LR功能。通过这样做，我们有效利用输入图像区域上的全局上下文信息，同时保持整个SR操作的低计算复杂度。另外，我们将边缘差异约束引入到我们的损失函数中以预处理边缘和纹理结构。大量的实验证明我们的方法优于现有的最先进的方法

##### URL
[http://arxiv.org/abs/1805.10143](http://arxiv.org/abs/1805.10143)

##### PDF
[http://arxiv.org/pdf/1805.10143](http://arxiv.org/pdf/1805.10143)

