---
layout: post
title: "Combining ConvNets with Hand-Crafted Features for Action Recognition Based on an HMM-SVM Classifier"
date: 2016-02-01 23:57:22
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Deep_Learning Recognition
author: Pichao Wang, Zhaoyang Li, Yonghong Hou, Wanqing Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new framework for RGB-D-based action recognition that takes advantages of hand-designed features from skeleton data and deeply learned features from depth maps, and exploits effectively both the local and global temporal information. Specifically, depth and skeleton data are firstly augmented for deep learning and making the recognition insensitive to view variance. Secondly, depth sequences are segmented using the hand-crafted features based on skeleton joints motion histogram to exploit the local temporal information. All training se gments are clustered using an Infinite Gaussian Mixture Model (IGMM) through Bayesian estimation and labelled for training Convolutional Neural Networks (ConvNets) on the depth maps. Thus, a depth sequence can be reliably encoded into a sequence of segment labels. Finally, the sequence of labels is fed into a joint Hidden Markov Model and Support Vector Machine (HMM-SVM) classifier to explore the global temporal information for final recognition.

##### Abstract (translated by Google)
本文提出了一种新的基于RGB-D的动作识别框架，该框架利用了来自骨架数据的手工设计特征和来自深度图的深度学习特征，有效地利用了局部和全局时间信息。具体而言，首先增加深度和骨架数据以进行深度学习，并使识别对视图变化不敏感。其次，使用基于骨架关节运动直方图的手工特征对深度序列进行分割，以利用局部时间信息。使用无限高斯混合模型（IGMM），通过贝叶斯估计对所有训练部分进行聚类，并将其标记为在深度图上训练卷积神经网络（ConvNets）。因此，深度序列可以可靠地编码成段标签序列。最后，将标签序列输入到联合隐马尔可夫模型和支持向量机（HMM-SVM）分类器中，以探索最终识别的全局时间信息。

##### URL
[https://arxiv.org/abs/1602.00749](https://arxiv.org/abs/1602.00749)

##### PDF
[https://arxiv.org/pdf/1602.00749](https://arxiv.org/pdf/1602.00749)

