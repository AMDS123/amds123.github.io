---
layout: post
title: "Deep Linear Discriminant Analysis on Fisher Networks: A Hybrid Architecture for Person Re-identification"
date: 2016-06-06 02:11:15
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Gradient_Descent
author: Lin Wu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification is to seek a correct match for a person of interest across views among a large number of imposters. It typically involves two procedures of non-linear feature extractions against dramatic appearance changes, and subsequent discriminative analysis in order to reduce intra- personal variations while enlarging inter-personal differences. In this paper, we introduce a hybrid architecture which combines Fisher vectors and deep neural networks to learn non-linear representations of person images to a space where data can be linearly separable. We reinforce a Linear Discriminant Analysis (LDA) on top of the deep neural network such that linearly separable latent representations can be learnt in an end-to-end fashion. By optimizing an objective function modified from LDA, the network is enforced to produce feature distributions which have a low variance within the same class and high variance between classes. The objective is essentially derived from the general LDA eigenvalue problem and allows to train the network with stochastic gradient descent and back-propagate LDA gradients to compute the gradients involved in Fisher vector encoding. For evaluation we test our approach on four benchmark data sets in person re-identification (VIPeR [1], CUHK03 [2], CUHK01 [3], and Market1501 [4]). Extensive experiments on these benchmarks show that our model can achieve state-of-the-art results.

##### Abstract (translated by Google)
人物重新认同是为了在一大批冒名顶替者之间为一个有意见的人寻找一个正确的匹配。它通常涉及两个程序的非线性特征提取对戏剧性的外观变化，以及随后的区别分析，以减少个人之间的差异，同时扩大个人间的差异。在本文中，我们介绍了一个混合架构，它结合了Fisher矢量和深度神经网络来学习人物图像的非线性表示到一个数据可以线性分离的空间。我们在深度神经网络之上加强了线性判别分析（LDA），使线性可分的潜在表示可以以端到端的方式学习。通过对LDA修正的目标函数进行优化，强制网络产生同类中方差较小，类间偏差较大的特征分布。这个目标本质上是从一般的LDA特征值问题得出的，并且允许用随机梯度下降和向后传播LDA梯度来训练网络，以计算Fisher矢量编码中涉及的梯度。为了评估，我们测试了我们的四种基准数据集（VIPeR [1]，CUHK03 [2]，CUHK01 [3]和Market1501 [4]）的方法。这些基准的大量实验表明，我们的模型可以达到最新的结果。

##### URL
[https://arxiv.org/abs/1606.01595](https://arxiv.org/abs/1606.01595)

##### PDF
[https://arxiv.org/pdf/1606.01595](https://arxiv.org/pdf/1606.01595)

