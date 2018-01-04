---
layout: post
title: "Cooperative Training of Deep Aggregation Networks for RGB-D Action Recognition"
date: 2017-12-05 07:33:20
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Classification Relation Recognition
author: Pichao Wang, Wanqing Li, Jun Wan, Philip Ogunbona, Xinwang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
A novel deep neural network training paradigm that exploits the conjoint information in multiple heterogeneous sources is proposed. Specifically, in a RGB-D based action recognition task, it cooperatively trains a single convolutional neural network (named c-ConvNet) on both RGB visual features and depth features, and deeply aggregates the two kinds of features for action recognition. Differently from the conventional ConvNet that learns the deep separable features for homogeneous modality-based classification with only one softmax loss function, the c-ConvNet enhances the discriminative power of the deeply learned features and weakens the undesired modality discrepancy by jointly optimizing a ranking loss and a softmax loss for both homogeneous and heterogeneous modalities. The ranking loss consists of intra-modality and cross-modality triplet losses, and it reduces both the intra-modality and cross-modality feature variations. Furthermore, the correlations between RGB and depth data are embedded in the c-ConvNet, and can be retrieved by either of the modalities and contribute to the recognition in the case even only one of the modalities is available. The proposed method was extensively evaluated on two large RGB-D action recognition datasets, ChaLearn LAP IsoGD and NTU RGB+D datasets, and one small dataset, SYSU 3D HOI, and achieved state-of-the-art results.

##### Abstract (translated by Google)
提出了一种新的深度神经网络训练范式，利用多个不同来源的联合信息。具体来说，在基于RGB-D的动作识别任务中，在RGB视觉特征和深度特征上合作训练单一卷积神经网络（命名为c-ConvNet），并深入聚合两种动作识别特征。与传统的ConvNet不同的是，c-ConvNet通过只有一个softmax损失函数来学习均匀模态分类的深度可分性特征，增强了深度学习特征的判别力，通过联合优化排序损失和减少不希望的形态差异同质和异质模态的软最大损失。排名损失包括内部模态和跨模态三元组损失，并且降低了模态内和跨模态特征变化。此外，RGB和深度数据之间的相关性被嵌入到c-ConvNet中，并且可以通过任何一种模式进行检索，并且有助于识别，即使只有一种模式可用。所提出的方法在两个大的RGB-D动作识别数据集ChaLearn LAP IsoGD和NTU RGB + D数据集以及一个小数据集SYSU 3D HOI上进行了广泛的评估，并获得了最新的结果。

##### URL
[http://arxiv.org/abs/1801.01080](http://arxiv.org/abs/1801.01080)

##### PDF
[http://arxiv.org/pdf/1801.01080](http://arxiv.org/pdf/1801.01080)

