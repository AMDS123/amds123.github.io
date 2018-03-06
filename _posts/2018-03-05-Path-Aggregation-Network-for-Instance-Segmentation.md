---
layout: post
title: "Path Aggregation Network for Instance Segmentation"
date: 2018-03-05 07:46:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Prediction Detection
author: Shu Liu, Lu Qi, Haifang Qin, Jianping Shi, Jiaya Jia
mathjax: true
---

* content
{:toc}

##### Abstract
The way that information propagates in neural networks is of great importance. In this paper, we propose Path Aggregation Network (PANet) aiming at boosting information flow in proposal-based instance segmentation framework. Specifically, we enhance the entire feature hierarchy with accurate localization signals in lower layers by bottom-up path augmentation, which shortens the information path between lower layers and topmost feature. We present adaptive feature pooling, which links feature grid and all feature levels to make useful information in each feature level propagate directly to following proposal subnetworks. A complementary branch capturing different views for each proposal is created to further improve mask prediction. These improvements are simple to implement, with subtle extra computational overhead. Our PANet reaches the 1st place in the COCO 2017 Challenge Instance Segmentation task and the 2nd place in Object Detection task without large-batch training. It is also state-of-the-art on MVD and Cityscapes.

##### Abstract (translated by Google)
信息在神经网络中传播的方式非常重要。在本文中，我们提出路径聚合网络（PANet），旨在提高基于提案的实例分割框架中的信息流。具体而言，我们通过自下而上的路径增强在较低层中使用精确的定位信号来增强整个特征层次结构，这缩短了较低层和最顶层特征之间的信息路径。我们提出了自适应特征池，它将特征网格和所有特征级别链接起来，使每个特征级别的有用信息直接传播到以下提案子网络。为每个提案捕获不同视图的补充分支被创建以进一步改善掩模预测。这些改进很容易实现，具有微妙的额外计算开销。我们的PANet在COCO 2017挑战实例细分任务中排名第一，并且在没有大批量培训的情况下在对象检测任务中排名第二。它也是MVD和城市景观的最新技术。

##### URL
[http://arxiv.org/abs/1803.01534](http://arxiv.org/abs/1803.01534)

##### PDF
[http://arxiv.org/pdf/1803.01534](http://arxiv.org/pdf/1803.01534)

