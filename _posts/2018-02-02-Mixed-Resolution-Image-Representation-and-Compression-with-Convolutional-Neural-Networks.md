---
layout: post
title: "Mixed-Resolution Image Representation and Compression with Convolutional Neural Networks"
date: 2018-02-02 08:57:44
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN
author: Lijun Zhao, Huihui Bai, Feng Li, Anhong Wang, Yao Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a end-to-end mixed-resolution image compression framework with convolutional neural networks. Firstly, given one input image, feature description neural network (FDNN) is used to generate a new representation of this image, so that this representation can be more efficiently compressed by standard coder, as compared to the input image. Furthermore, we use post-processing neural network (PPNN) to remove the coding artifacts caused by quantization of codec. Secondly, low-resolution representation is considered under low bit-rate for high efficiency compression in terms of most of bit spent by image's structures. However, more bits should be assigned to image details in the high-resolution, when most of structures have been kept after compression at the high bit-rate. This comes from that the low-resolution representation can't burden more information than high-resolution representation beyond a certain bit-rate. Finally, to resolve the problem of error back-propagation from the PPNN network to the FDNN network, we introduce a virtual codec neural network to intimate the procedure of standard compression and post-processing. The objective experimental results have demonstrated the proposed method has a large margin improvement, when comparing with several state-of-the-art approaches.

##### Abstract (translated by Google)
在本文中，我们提出了一种具有卷积神经网络的端到端混合分辨率图像压缩框架。首先，给定一个输入图像，使用特征描述神经网络（FDNN）生成该图像的新表示，从而与输入图像相比，该表示可以由标准编码器更高效地压缩。此外，我们使用后处理神经网络（PPNN）去除由编解码器量化引起的编码伪影。其次，对于高效压缩，在低比特率下考虑低分辨率表示，就图像结构所花费的大部分而言。然而，当高比特率压缩后大部分结构被保留时，应该以高分辨率将更多比特分配给图像细节。这是由于低分辨率表示不能比超过一定比特率的高分辨率表示负担更多的信息。最后，为了解决从PPNN网络到FDNN网络的错误反向传播问题，我们引入了一个虚拟编解码器神经网络来实现标准压缩和后处理的过程。客观的实验结果表明，与几种最先进的方法相比，所提出的方法有很大的改善余地。

##### URL
[http://arxiv.org/abs/1802.01447](http://arxiv.org/abs/1802.01447)

##### PDF
[http://arxiv.org/pdf/1802.01447](http://arxiv.org/pdf/1802.01447)

