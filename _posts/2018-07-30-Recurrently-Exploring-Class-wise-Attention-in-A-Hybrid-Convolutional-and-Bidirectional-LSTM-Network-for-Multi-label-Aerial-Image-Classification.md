---
layout: post
title: "Recurrently Exploring Class-wise Attention in A Hybrid Convolutional and Bidirectional LSTM Network for Multi-label Aerial Image Classification"
date: 2018-07-30 09:14:15
categories: arXiv_CV
tags: arXiv_CV Attention CNN Image_Classification RNN Classification Quantitative Relation
author: Yuansheng Hua, Lichao Mou, Xiao Xiang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Aerial image classification is of great significance in remote sensing community, and many researches have been conducted over the past few years. Among these studies, most of them focus on categorizing an image into one semantic label, while in the real world, an aerial image is often associated with multiple labels, e.g., multiple object-level labels in our case. Besides, a comprehensive picture of present objects in a given high resolution aerial image can provide more in-depth understanding of the studied region. For these reasons, aerial image multi-label classification has been attracting increasing attention. However, one common limitation shared by existing methods in the community is that the co-occurrence relationship of various classes, so called class dependency, is underexplored and leads to an inconsiderate decision. In this paper, we propose a novel end-to-end network, namely class-wise attention-based convolutional and bidirectional LSTM network (CA-Conv-BiLSTM), for this task. The proposed network consists of three indispensable components: 1) a feature extraction module, 2) a class attention learning layer, and 3) a bidirectional LSTM-based sub-network. Particularly, the feature extraction module is designed for extracting fine-grained semantic feature maps, while the class attention learning layer aims at capturing discriminative class-specific features. As the most important part, the bidirectional LSTM-based sub-network models the underlying class dependency in both directions and produce structured multiple object labels. Experimental results on UCM multi-label dataset and DFC15 multi-label dataset validate the effectiveness of our model quantitatively and qualitatively.

##### Abstract (translated by Google)
航空影像分类在遥感界具有重要意义，近几年来进行了大量的研究。在这些研究中，大多数研究侧重于将图像分类为一个语义标签，而在现实世界中，空间图像通常与多个标签相关联，例如，在我们的情况下，多个对象级标签。此外，在给定的高分辨率航拍图像中对现有物体的全面描绘可以提供对所研究区域的更深入的理解。由于这些原因，航拍图像多标签分类已经引起越来越多的关注。然而，社区中现有方法共有的一个共同限制是，各种类的共现关系，即所谓的类依赖性，未得到充分探索，并导致一个不体面的决定。在本文中，我们提出了一种新颖的端到端网络，即基于类的注意力卷积和双向LSTM网络（CA-Conv-BiLSTM），用于此任务。所提出的网络包括三个必不可少的组件：1）特征提取模块，2）类注意力学习层，以及3）基于双向LSTM的子网络。特别地，特征提取模块被设计用于提取细粒度语义特征图，而类注意力学习层旨在捕获辨别特定类特征。作为最重要的部分，基于双向LSTM的子网络在两个方向上模拟基础类依赖性并产生结构化多个对象标签。 UCM多标签数据集和DFC15多标签数据集的实验结果可以定量和定性地验证模型的有效性。

##### URL
[http://arxiv.org/abs/1807.11245](http://arxiv.org/abs/1807.11245)

##### PDF
[http://arxiv.org/pdf/1807.11245](http://arxiv.org/pdf/1807.11245)

