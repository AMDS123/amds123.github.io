---
layout: post
title: "Scalable Compression of Deep Neural Networks"
date: 2016-08-26 05:08:24
categories: arXiv_CV
tags: arXiv_CV
author: Xing Wang, Jie Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks generally involve some layers with mil- lions of parameters, making them difficult to be deployed and updated on devices with limited resources such as mobile phones and other smart embedded systems. In this paper, we propose a scalable representation of the network parameters, so that different applications can select the most suitable bit rate of the network based on their own storage constraints. Moreover, when a device needs to upgrade to a high-rate network, the existing low-rate network can be reused, and only some incremental data are needed to be downloaded. We first hierarchically quantize the weights of a pre-trained deep neural network to enforce weight sharing. Next, we adaptively select the bits assigned to each layer given the total bit budget. After that, we retrain the network to fine-tune the quantized centroids. Experimental results show that our method can achieve scalable compression with graceful degradation in the performance.

##### Abstract (translated by Google)
深度神经网络通常包含一些具有数百个参数的层，使得在有限资源的设备（如手机和其他智能嵌入式系统）上难以部署和更新。在本文中，我们提出了一个可扩展的网络参数表示，以便不同的应用程序可以根据自己的存储约束来选择网络的最合适的比特率。而且，当设备需要升级到高速网络时，现有的低速网络可以重用，只需要下载一些增量数据即可。我们首先分层次地量化预先训练的深度神经网络的权重来加强分量。接下来，我们根据总比特预算自适应地选择分配给每个层的比特。之后，我们重新训练网络来微调量化质心。实验结果表明，我们的方法可以实现可伸缩的压缩，并且性能下降较好。

##### URL
[https://arxiv.org/abs/1608.07365](https://arxiv.org/abs/1608.07365)

##### PDF
[https://arxiv.org/pdf/1608.07365](https://arxiv.org/pdf/1608.07365)

