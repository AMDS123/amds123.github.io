---
layout: post
title: "Speeding-up Object Detection Training for Robotics with FALKON"
date: 2018-03-23 11:13:29
categories: arXiv_AI
tags: arXiv_AI Object_Detection Deep_Learning Detection
author: Elisa Maiettini, Giulia Pasquale, Lorenzo Rosasco, Lorenzo Natale
mathjax: true
---

* content
{:toc}

##### Abstract
Latest deep learning methods for object detection provided remarkable performance boost, but have limits when used in robotic applications. One of the most relevant issues is the long training time, which is due to the large size and unbalance of the associated training sets, characterized by few positive and tons of negative (i.e. background) examples. Proposed approaches, either based on end-to-end learning by back-propagation [22], or standard kernel methods trained with Hard Negatives Mining on top of deep features [8], proved to be effective, but prohibitively slow for on-line applications. In this paper we propose a novel pipeline for object detection that overcomes this problem and provides comparable performance, with a 60x training speedup. Our pipeline combines (i) the Region Proposal Network and the deep feature extractor from [22] to efficiently select candidate RoIs and encode them into powerful representations, with (ii) the recently proposed FALKON [23] algorithm, a novel kernel-based method that allows to quickly train on millions of points. We address the size and unbalance of training data by exploiting the stochastic subsampling intrinsic into the method, combined with a novel, fast, bootstrapping approach. We assess the effectiveness of the approach in a standard computer vision setting (PASCAL VOC 2007 [5]) and demonstrate its applicability to a real robotic scenario as represented by the iCubWorld Transformations [18] dataset.

##### Abstract (translated by Google)
最新的物体检测深度学习方法提供了显着的性能提升，但在机器人应用中使用时会受到限制。最相关的问题之一是训练时间长，这是由于相关训练集的大小和不平衡造成的，其特征在于很少的正数和负数（即背景）例子。提出的方法，无论是基于反向传播的端到端学习[22]，还是在深度特征之上用硬阴性挖掘训练的标准核心方法[8]，都被证明是有效的，但是对于在线应用。在本文中，我们提出了一种新颖的物体检测流水线，克服了这个问题，并提供了与60倍训练加速相当的性能。我们的流程结合了（i）区域提议网络和[22]中的深度特征提取器，以有效地选择候选RoI并将它们编码成强大的表示，其中（ii）最近提出的FALKON [23]算法，一种新的基于内核的方法可以快速训练数百万分。我们通过利用方法中固有的随机子采样，结合一种新颖的，快速的自举方法来解决训练数据的大小和不平衡问题。我们评估标准计算机视觉设置（PASCAL VOC 2007 [5]）中该方法的有效性，并证明其适用于由iCubWorld Transformations [18]数据集表示的真实机器人场景。

##### URL
[https://arxiv.org/abs/1803.08740](https://arxiv.org/abs/1803.08740)

##### PDF
[https://arxiv.org/pdf/1803.08740](https://arxiv.org/pdf/1803.08740)

