---
layout: post
title: "Stacked Deconvolutional Network for Semantic Segmentation"
date: 2017-08-16 15:35:02
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Optimization
author: Jun Fu, Jing Liu, Yuhang Wang, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progress in semantic segmentation has been driven by improving the spatial resolution under Fully Convolutional Networks (FCNs). To address this problem, we propose a Stacked Deconvolutional Network (SDN) for semantic segmentation. In SDN, multiple shallow deconvolutional networks, which are called as SDN units, are stacked one by one to integrate contextual information and guarantee the fine recovery of localization information. Meanwhile, inter-unit and intra-unit connections are designed to assist network training and enhance feature fusion since the connections improve the flow of information and gradient propagation throughout the network. Besides, hierarchical supervision is applied during the upsampling process of each SDN unit, which guarantees the discrimination of feature representations and benefits the network optimization. We carry out comprehensive experiments and achieve the new state-of-the-art results on three datasets, including PASCAL VOC 2012, CamVid, GATECH. In particular, our best model without CRF post-processing achieves an intersection-over-union score of 86.6% in the test set.

##### Abstract (translated by Google)
最近在语义分割方面的进展是由完全卷积网络（FCNs）下的空间分辨率的提高所驱动的。为了解决这个问题，我们提出了一个用于语义分割的叠层去卷积网络（SDN）。在SDN中，被称为SDN单元的多个浅层反卷积网络被逐一堆叠，以整合上下文信息，并保证本地化信息的良好恢复。同时，单元间和单元内连接被设计成协助网络训练和增强特征融合，因为连接改善了整个网络中的信息流和梯度传播。另外，在每个SDN单元的上采样过程中采用分层监管，保证了特征表征的识别，有利于网络优化。我们进行了全面的实验，并在PASCAL VOC 2012，CamVid，GATECH三个数据集上获得了最新的最新成果。特别是，我们没有CRF后处理的最佳模型在测试集合中达到了86.6％的交叉交叉分数。

##### URL
[https://arxiv.org/abs/1708.04943](https://arxiv.org/abs/1708.04943)

##### PDF
[https://arxiv.org/pdf/1708.04943](https://arxiv.org/pdf/1708.04943)

