---
layout: post
title: "Residual Dense Network for Image Super-Resolution"
date: 2018-02-24 04:40:06
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yulun Zhang, Yapeng Tian, Yu Kong, Bineng Zhong, Yun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
A very deep convolutional neural network (CNN) has recently achieved great success for image super-resolution (SR) and offered hierarchical features as well. However, most deep CNN based SR models do not make full use of the hierarchical features from the original low-resolution (LR) images, thereby achieving relatively-low performance. In this paper, we propose a novel residual dense network (RDN) to address this problem in image SR. We fully exploit the hierarchical features from all the convolutional layers. Specifically, we propose residual dense block (RDB) to extract abundant local features via dense connected convolutional layers. RDB further allows direct connections from the state of preceding RDB to all the layers of current RDB, leading to a contiguous memory (CM) mechanism. Local feature fusion in RDB is then used to adaptively learn more effective features from preceding and current local features and stabilizes the training of wider network. After fully obtaining dense local features, we use global feature fusion to jointly and adaptively learn global hierarchical features in a holistic way. Extensive experiments on benchmark datasets with different degradation models show that our RDN achieves favorable performance against state-of-the-art methods.

##### Abstract (translated by Google)
一个非常深的卷积神经网络（CNN）最近在图像超分辨率（SR）方面取得了巨大的成功，并提供了分层特征。然而，大多数基于CNN的深层次的SR模型并没有充分利用原始低分辨率（LR）图像的分层特征，从而达到相对较低的性能。在本文中，我们提出了一种新的残留密集网络（RDN）来解决图像SR中的这个问题。我们充分利用所有卷积层的层次特征。具体来说，我们提出了残余密集块（RDB），以通过密集连通卷积层提取丰富的局部特征。 RDB还允许从前一个RDB的状态直接连接到当前RDB的所有层，从而形成连续的内存（CM）机制。然后使用RDB中的局部特征融合来自适应地学习来自先前和当前局部特征的更有效特征，并稳定更广泛网络的训练。在完全获得稠密的局部特征之后，我们使用全局特征融合以整体方式联合和自适应地学习全局分层特征。对具有不同降级模型的基准数据集进行的大量实验表明，我们的RDN对照最先进的方法取得了良好的性能。

##### URL
[http://arxiv.org/abs/1802.08797](http://arxiv.org/abs/1802.08797)

##### PDF
[http://arxiv.org/pdf/1802.08797](http://arxiv.org/pdf/1802.08797)

