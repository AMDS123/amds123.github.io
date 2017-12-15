---
layout: post
title: "High-performance Semantic Segmentation Using Very Deep Fully Convolutional Networks"
date: 2016-04-15 02:52:46
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Zifeng Wu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for high-performance semantic image segmentation (or semantic pixel labelling) based on very deep residual networks, which achieves the state-of-the-art performance. A few design factors are carefully considered to this end. We make the following contributions. (i) First, we evaluate different variations of a fully convolutional residual network so as to find the best configuration, including the number of layers, the resolution of feature maps, and the size of field-of-view. Our experiments show that further enlarging the field-of-view and increasing the resolution of feature maps are typically beneficial, which however inevitably leads to a higher demand for GPU memories. To walk around the limitation, we propose a new method to simulate a high resolution network with a low resolution network, which can be applied during training and/or testing. (ii) Second, we propose an online bootstrapping method for training. We demonstrate that online bootstrapping is critically important for achieving good accuracy. (iii) Third we apply the traditional dropout to some of the residual blocks, which further improves the performance. (iv) Finally, our method achieves the currently best mean intersection-over-union 78.3\% on the PASCAL VOC 2012 dataset, as well as on the recent dataset Cityscapes.

##### Abstract (translated by Google)
我们提出了一个基于非常深的残留网络的高性能语义图像分割（或语义像素标记）的方法，实现了最先进的性能。为此，我们仔细考虑了一些设计因素。我们做出以下贡献。 （i）首先，我们评估完全卷积残差网络的不同变化，以找到最佳配置，包括层数，特征映射的分辨率和视野的大小。我们的实验表明，进一步扩大视野和提高特征图的分辨率通常是有利的，然而不可避免地导致对GPU存储器的更高需求。为了解决这个限制，我们提出了一种新的方法来模拟一个低分辨率网络的高分辨率网络，这个网络可以在训练和/或测试过程中使用。 （ii）其次，我们提出一个在线引导训练的方法。我们证明，在线bootstrapping对于实现良好的准确性至关重要。 （三）我们把传统的辍学运用于一些残余的街区，这进一步提高了表现。 （iv）最后，我们的方法在PASCAL VOC 2012数据集以及最近的数据集Cityscapes上实现了目前最好的平均交叉点比率78.3％。

##### URL
[https://arxiv.org/abs/1604.04339](https://arxiv.org/abs/1604.04339)

##### PDF
[https://arxiv.org/pdf/1604.04339](https://arxiv.org/pdf/1604.04339)

