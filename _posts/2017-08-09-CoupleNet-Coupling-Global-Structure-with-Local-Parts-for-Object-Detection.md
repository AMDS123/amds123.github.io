---
layout: post
title: "CoupleNet: Coupling Global Structure with Local Parts for Object Detection"
date: 2017-08-09 15:07:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Yousong Zhu, Chaoyang Zhao, Jinqiao Wang, Xu Zhao, Yi Wu, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
The region-based Convolutional Neural Network (CNN) detectors such as Faster R-CNN or R-FCN have already shown promising results for object detection by combining the region proposal subnetwork and the classification subnetwork together. Although R-FCN has achieved higher detection speed while keeping the detection performance, the global structure information is ignored by the position-sensitive score maps. To fully explore the local and global properties, in this paper, we propose a novel fully convolutional network, named as CoupleNet, to couple the global structure with local parts for object detection. Specifically, the object proposals obtained by the Region Proposal Network (RPN) are fed into the the coupling module which consists of two branches. One branch adopts the position-sensitive RoI (PSRoI) pooling to capture the local part information of the object, while the other employs the RoI pooling to encode the global and context information. Next, we design different coupling strategies and normalization ways to make full use of the complementary advantages between the global and local branches. Extensive experiments demonstrate the effectiveness of our approach. We achieve state-of-the-art results on all three challenging datasets, i.e. a mAP of 82.7% on VOC07, 80.4% on VOC12, and 34.4% on COCO. Codes will be made publicly available.

##### Abstract (translated by Google)
基于区域的卷积神经网络（CNN）检测器，如R-CNN或R-FCN，已经将区域提议子网络和分类子网络结合在一起，在检测目标方面已经取得了令人满意的结果。尽管R-FCN在保持检测性能的同时实现了更高的检测速度，但是位置敏感分数图忽略了全局结构信息。为了充分发掘本地和全局属性，本文提出了一种新的全卷积网络 -  CoupleNet，将全局结构与局部部分耦合起来进行目标检测。具体来说，由区域提议网络（RPN）获得的目标提议被馈送到由两个分支组成的耦合模块中。一个分支采用位置敏感的RoI（PSRoI）池捕获对象的本地部分信息，另一个分支采用RoI池对全局和上下文信息进行编码。接下来，我们设计不同的耦合策略和规范化方式，充分利用全球和地方分支机构的互补优势。大量的实验证明了我们的方法的有效性。我们在所有三个具有挑战性的数据集上获得了最先进的结果，即VOC07分别为82.7％，VOC12为80.4％，COCO为34.4％。代码将公开。

##### URL
[https://arxiv.org/abs/1708.02863](https://arxiv.org/abs/1708.02863)

##### PDF
[https://arxiv.org/pdf/1708.02863](https://arxiv.org/pdf/1708.02863)

