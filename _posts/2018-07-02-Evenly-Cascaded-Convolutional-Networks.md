---
layout: post
title: "Evenly Cascaded Convolutional Networks"
date: 2018-07-02 04:12:16
categories: arXiv_CV
tags: arXiv_CV CNN
author: Chengxi Ye, Chinmaya Devaraj, Michael Maynord, Cornelia Ferm&#xfc;ller, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we demonstrate that state-of-the-art convolutional neural networks can be constructed using a cascade algorithm for deep networks, inspired by the cascade algorithm in wavelet analysis. 
 For each network layer the cascade algorithm creates two streams of features from the previous layer: one stream modulates the existing features producing low-level features, the other stream produces new features of a higher level. We evenly structure our network by resizing feature map dimensions by a consistent ratio. 
 Our network produces humanly interpretable features maps, a result whose intuition can be understood in the context of scale-space theory. We demonstrate that our cascaded design facilitates the training process through providing easily trainable shortcuts. We report new state-of-the-art results for small networks - a consequence of our architecture's simple structure and direct training, without the need for additional treatment such as pruning or compression. Our 6-cascading-layer design with under 500k parameters achieves 95.24% and 78.99% accuracy on CIFAR-10 and CIFAR-100 datasets, respectively.

##### Abstract (translated by Google)
在本文中，我们证明了最先进的卷积神经网络可以使用级联算法构建深度网络，其灵感来自小波分析中的级联算法。
 对于每个网络层，级联算法从前一层创建两个特征流：一个流调制现有特征，产生低级特征，另一个流产生更高级别的新特征。我们通过以一致的比例调整特征地图尺寸来均匀地构建我们的网络。
 我们的网络产生人性可解释的特征图，这种结果的直觉可以在尺度空间理论的背景下理解。我们证明了我们的级联设计通过提供易于训练的快捷方式来促进培训过程。我们为小型网络报告了最新的最新结果 - 这是我们的架构结构简单，直接培训的结果，无需修剪或压缩等额外处理。我们的6级联设计，参数低于500k，分别在CIFAR-10和CIFAR-100数据集上实现了95.24％和78.99％的准确度。

##### URL
[http://arxiv.org/abs/1807.00456](http://arxiv.org/abs/1807.00456)

##### PDF
[http://arxiv.org/pdf/1807.00456](http://arxiv.org/pdf/1807.00456)

