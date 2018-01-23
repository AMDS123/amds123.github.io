---
layout: post
title: "Multiple Description Convolutional Neural Networks for Image Compression"
date: 2018-01-20 01:28:20
categories: arXiv_CV
tags: arXiv_CV CNN
author: Lijun Zhao, Huihui Bai, Anhong Wang, Yao Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple description coding (MDC) is able to stably transmit the signal in the un-reliable and non-prioritized networks, which has been broadly studied for several decades. However, the traditional MDC doesn't well leverage image's context features to generate multiple descriptions. In this paper, we propose a novel standard-compliant convolutional neural network-based MDC framework in term of image's context features. Firstly, multiple description generator network (MDGN) is designed to produce appearance-similar yet feature-different multiple descriptions automatically according to image's content, which are compressed by standard codec. Secondly, we present multiple description reconstruction network (MDRN) including side reconstruction network (SRN) and central reconstruction network (CRN). When any one of two lossy descriptions is received at the decoder, SRN network is used to improve the quality of this decoded lossy description by removing the compression artifact and up-sampling simultaneously. Meanwhile, we utilize CRN network with two decoded descriptions as inputs for better reconstruction, if both of lossy descriptions are available. Thirdly, multiple description virtual codec network (MDVCN) is proposed to bridge the gap between MDGN network and MDRN network in order to train an end-to-end MDC framework. Here, two learning algorithms are provided to train our whole framework. In addition to structural similarity loss function, the produced descriptions are used as opposing labels with multiple description distance loss function to regularize the training of MDGN network. These losses guarantee that the generated description images are structurally similar yet finely diverse. Experimental results show a great deal of objective and subjective quality measurements to validate the efficiency of the proposed method.

##### Abstract (translated by Google)
多描述编码（MDC）能够在不可靠和非优先的网络中稳定传输信号，这已经被广泛研究了几十年。然而，传统的MDC不能很好地利用图像的上下文特征来生成多个描述。在本文中，我们根据图像的上下文特征提出了一种新的符合标准的基于卷积神经网络的MDC框架。首先，设计了多描述生成器网络（MDGN），根据图像内容自动生成外观相似，但特征不同的多描述，由标准编解码器进行压缩。其次，提出了包括边重建网络（SRN）和中心重建网络（CRN）在内的多描述重建网络（MDRN）。当解码器收到两个有损描述中的任何一个时，SRN网络通过同时去除压缩伪像和上采样来提高解码有损描述的质量。同时，如果两个有损描述都可用，我们利用CRN网络和两个解码描述作为更好的重构输入。再次，提出了多描述虚拟编解码网络（MDVCN），以弥合MDGN网络与MDRN网络之间的差距，以培养端到端的MDC架构。这里提供了两种学习算法来训练我们的整个框架。除了结构相似性损失函数之外，所生成的描述被用作具有多重描述距离损失函数的反向标签来规范MDGN网络的训练。这些损失保证了所生成的描述图像在结构上相似而又精细多样。实验结果显示了大量客观和主观的质量测量来验证所提出的方法的效率。

##### URL
[https://arxiv.org/abs/1801.06611](https://arxiv.org/abs/1801.06611)

##### PDF
[https://arxiv.org/pdf/1801.06611](https://arxiv.org/pdf/1801.06611)

