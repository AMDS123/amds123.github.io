---
layout: post
title: "Speeding-up Object Detection Training for Robotics with FALKON"
date: 2018-08-27 15:19:38
categories: arXiv_AI
tags: arXiv_AI Object_Detection Deep_Learning Detection
author: Elisa Maiettini, Giulia Pasquale, Lorenzo Rosasco, Lorenzo Natale
mathjax: true
---

* content
{:toc}

##### Abstract
Latest deep learning methods for object detection provide remarkable performance, but have limits when used in robotic applications. One of the most relevant issues is the long training time, which is due to the large size and imbalance of the associated training sets, characterized by few positive and a large number of negative examples (i.e. background). Proposed approaches are based on end-to-end learning by back-propagation [22] or kernel methods trained with Hard Negatives Mining on top of deep features [8]. These solutions are effective, but prohibitively slow for on-line applications. In this paper we propose a novel pipeline for object detection that overcomes this problem and provides comparable performance, with a 60x training speedup. Our pipeline combines (i) the Region Proposal Network and the deep feature extractor from [22] to efficiently select candidate RoIs and encode them into powerful representations, with (ii) the FALKON [23] algorithm, a novel kernel-based method that allows fast training on large scale problems (millions of points). We address the size and imbalance of training data by exploiting the stochastic subsampling intrinsic into the method and a novel, fast, bootstrapping approach. We assess the effectiveness of the approach on a standard Computer Vision dataset (PASCAL VOC 2007 [5]) and demonstrate its applicability to a real robotic scenario with the iCubWorld Transformations [18] dataset.

##### Abstract (translated by Google)
用于物体检测的最新深度学习方法提供了显着的性能，但在机器人应用中具有限制。最相关的问题之一是长训练时间，这是由于相关训练集的大尺寸和不平衡，其特征在于很少有正面和大量负面例子（即背景）。提出的方法基于反向传播的端到端学习[22]或在深度特征之上使用硬负面挖掘训练的核方法[8]。这些解决方案是有效的，但对于在线应用来说却非常慢。在本文中，我们提出了一种新颖的物体检测管道，它可以克服这个问题并提供可比性能，并具有60倍的训练加速。我们的管道结合了（i）区域提议网络和[22]的深度特征提取器，有效地选择候选RoI并将它们编码为强大的表示，其中包括（ii）FALKON [23]算法，这是一种新的基于内核的方法，允许快速培训大规模问题（数百万点）。我们通过利用该方法内在的随机子采样和一种新颖，快速，自举的方法来解决训练数据的大小和不平衡问题。我们评估该方法在标准计算机视觉数据集（PASCAL VOC 2007 [5]）上的有效性，并使用iCubWorld Transformations [18]数据集证明其对真实机器人场景的适用性。

##### URL
[http://arxiv.org/abs/1803.08740](http://arxiv.org/abs/1803.08740)

##### PDF
[http://arxiv.org/pdf/1803.08740](http://arxiv.org/pdf/1803.08740)

