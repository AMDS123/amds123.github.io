---
layout: post
title: "Deep LDA-Pruned Nets for Efficient Facial Gender Classification"
date: 2017-10-31 00:00:20
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation Recognition
author: Qing Tian, Tal Arbel, James J. Clark
mathjax: true
---

* content
{:toc}

##### Abstract
Many real-time tasks, such as human-computer interaction, require fast and efficient facial gender classification. Although deep CNN nets have been very effective for a multitude of classification tasks, their high space and time demands make them impractical for personal computers and mobile devices without a powerful GPU. In this paper, we develop a 16-layer, yet lightweight, neural network which boosts efficiency while maintaining high accuracy. Our net is pruned from the VGG-16 model starting from the last convolutional (conv) layer where we find neuron activations are highly uncorrelated given the gender. Through Fisher's Linear Discriminant Analysis (LDA), we show that this high decorrelation makes it safe to discard directly last conv layer neurons with high within-class variance and low between-class variance. Combined with either Support Vector Machines (SVM) or Bayesian classification, the reduced CNNs are capable of achieving comparable (or even higher) accuracies on the LFW and CelebA datasets than the original net with fully connected layers. On LFW, only four Conv5_3 neurons are able to maintain a comparably high recognition accuracy, which results in a reduction of total network size by a factor of 70X with a 11 fold speedup. Comparisons with a state-of-the-art pruning method as well as two smaller nets in terms of accuracy loss and convolutional layers pruning rate are also provided.

##### Abstract (translated by Google)
许多实时任务，如人机交互，都要求快速高效的面部性别分类。尽管CNN深层网络对于大量的分类任务来说非常有效，但是他们的高空间和时间要求使得它们在没有强大GPU的个人计算机和移动设备上不切实际。在本文中，我们开发了一个16层，但轻量级的神经网络，在保持高精度的同时提高了效率。我们的网络从VGG-16模型开始修剪，从最后的卷积（conv）层开始，我们发现神经元激活与性别高度不相关。通过Fisher线性判别分析（LDA），我们证明了这种高度的去相关性使得直接丢弃具有高级内方差和低级间方差的最后一个conv层神经元是安全的。结合支持向量机（SVM）或贝叶斯分类，减少的CNN能够在LFW和CelebA数据集上实现与具有完全连接层的原始网络相当（甚至更高）的精度。在LFW上，只有四个Conv5_3神经元能够保持相当高的识别精度，这导致整个网络尺寸减少了70倍，并且加速了11倍。还提供了与最先进的修剪方法以及精度损失和卷积层修剪速率方面的两个较小的网络的比较。

##### URL
[https://arxiv.org/abs/1704.06305](https://arxiv.org/abs/1704.06305)

##### PDF
[https://arxiv.org/pdf/1704.06305](https://arxiv.org/pdf/1704.06305)

