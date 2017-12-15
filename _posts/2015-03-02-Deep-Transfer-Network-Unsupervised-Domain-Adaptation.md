---
layout: post
title: "Deep Transfer Network: Unsupervised Domain Adaptation"
date: 2015-03-02 16:17:06
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Xu Zhang, Felix Xinnan Yu, Shih-Fu Chang, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation aims at training a classifier in one dataset and applying it to a related but not identical dataset. One successfully used framework of domain adaptation is to learn a transformation to match both the distribution of the features (marginal distribution), and the distribution of the labels given features (conditional distribution). In this paper, we propose a new domain adaptation framework named Deep Transfer Network (DTN), where the highly flexible deep neural networks are used to implement such a distribution matching process. This is achieved by two types of layers in DTN: the shared feature extraction layers which learn a shared feature subspace in which the marginal distributions of the source and the target samples are drawn close, and the discrimination layers which match conditional distributions by classifier transduction. We also show that DTN has a computation complexity linear to the number of training samples, making it suitable to large-scale problems. By combining the best paradigms in both worlds (deep neural networks in recognition, and matching marginal and conditional distributions in domain adaptation), we demonstrate by extensive experiments that DTN improves significantly over former methods in both execution time and classification accuracy.

##### Abstract (translated by Google)
领域适应的目标是在一个数据集中训练一个分类器并将其应用于相关但不相同的数据集。一个成功使用的领域适应框架是学习一个变换来匹配特征的分布（边际分布）和给定特征（条件分布）的标签分布。在本文中，我们提出了一个名为深度传输网络（DTN）的新的领域适应框架，其中使用高度灵活的深度神经网络来实现这种分布匹配过程。这是通过DTN中的两种类型的层实现的：共享特征提取层学习源和目标样本的边缘分布相近的共享特征子空间，以及通过分类器转换匹配条件分布的判别层。我们还表明，DTN的计算复杂度与训练样本的数量是线性的，适合于大规模的问题。通过结合两个世界中最好的范例（深度神经网络的识别，以及匹配领域适应中的边际和条件分布），我们通过广泛的实验证明DTN在执行时间和分类准确度方面比以前的方法显着改善。

##### URL
[https://arxiv.org/abs/1503.00591](https://arxiv.org/abs/1503.00591)

##### PDF
[https://arxiv.org/pdf/1503.00591](https://arxiv.org/pdf/1503.00591)

