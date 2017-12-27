---
layout: post
title: "Brain Tumor Segmentation Based on Refined Fully Convolutional Neural Networks with A Hierarchical Dice Loss"
date: 2017-12-25 16:06:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Classification Detection Relation
author: Jiachi Zhang, Xiaolei Shen, Tianqi Zhuo, Hong Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
As a basic task in computer vision, semantic segmentation can provide fundamental information for object detection and instance segmentation to help the artificial intelligence better understand real world. Since the proposal of fully convolutional neural network (FCNN), it has been widely used in semantic segmentation because of its high accuracy of pixel-wise classification as well as high precision of localization. In this paper, we apply several famous FCNN to brain tumor segmentation, making comparisons and adjusting network architectures to achieve better performance measured by metrics such as precision, recall, mean of intersection of union (mIoU) and dice score coefficient (DSC). The adjustments to the classic FCNN include adding more connections between convolutional layers, enlarging decoders after up sample layers and changing the way shallower layers' information is reused. Besides the structure modification, we also propose a new classifier with a hierarchical dice loss. Inspired by the containing relationship between classes, the loss function converts multiple classification to multiple binary classification in order to counteract the negative effect caused by imbalance data set. Massive experiments have been done on the training set and testing set in order to assess our refined fully convolutional neural networks and new types of loss function. Competitive figures prove they are more effective than their predecessors.

##### Abstract (translated by Google)
作为计算机视觉的基础任务之一，语义分割可以为物体检测和实例分割提供基础信息，帮助人工智能更好地理解真实世界。由于完全卷积神经网络（FCNN）的提出，由于它具有像素级分类的高精度和定位精度，因此被广泛应用于语义分割。本文将几种着名的FCNN应用于脑肿瘤分割，通过比较和调整网络结构，以精度，召回率，联合平均值（mIoU）和骰子评分系数（DSC）等指标来衡量更好的性能。对经典FCNN的调整包括在卷积层之间增加更多的连接，在上样层之后放大解码器并且改变浅层信息的重用方式。除了结构修改之外，我们还提出了一种新的分层丢包分类器。受类之间包含关系的启发，损失函数将多个分类转换为多个二元分类，以抵消不平衡数据集造成的负面影响。已经对训练集和测试集进行了大量实验，以评估我们完善的完全卷积神经网络和新类型的损失函数。有竞争力的数字证明他们比前辈更有效。

##### URL
[http://arxiv.org/abs/1712.09093](http://arxiv.org/abs/1712.09093)

##### PDF
[http://arxiv.org/pdf/1712.09093](http://arxiv.org/pdf/1712.09093)

