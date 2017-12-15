---
layout: post
title: "Deep Interactive Object Selection"
date: 2016-03-13 15:42:34
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Optimization Deep_Learning
author: Ning Xu, Brian Price, Scott Cohen, Jimei Yang, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Interactive object selection is a very important research problem and has many applications. Previous algorithms require substantial user interactions to estimate the foreground and background distributions. In this paper, we present a novel deep learning based algorithm which has a much better understanding of objectness and thus can reduce user interactions to just a few clicks. Our algorithm transforms user provided positive and negative clicks into two Euclidean distance maps which are then concatenated with the RGB channels of images to compose (image, user interactions) pairs. We generate many of such pairs by combining several random sampling strategies to model user click patterns and use them to fine tune deep Fully Convolutional Networks (FCNs). Finally the output probability maps of our FCN 8s model is integrated with graph cut optimization to refine the boundary segments. Our model is trained on the PASCAL segmentation dataset and evaluated on other datasets with different object classes. Experimental results on both seen and unseen objects clearly demonstrate that our algorithm has a good generalization ability and is superior to all existing interactive object selection approaches.

##### Abstract (translated by Google)
交互式对象选择是一个非常重要的研究问题，有很多的应用。以前的算法需要大量的用户交互来估计前景和背景分布。在本文中，我们提出了一种新颖的基于深度学习的算法，对对象有更好的理解，因此可以减少用户的交互，只需点击几下。我们的算法将用户提供的正面和负面点击转换为两个欧氏距离图，然后与图像的RGB通道连接组成（图像，用户交互）对。我们通过组合多个随机采样策略来生成许多这样的对，以模拟用户点击模式并使用它们来微调深度全卷积网络（FCN）。最后，我们的FCN 8s模型的输出概率图与图切割优化整合，以细化边界线段。我们的模型在PASCAL分割数据集上进行训练，并在其他数据集上使用不同的对象类进行评估。实验结果清楚地表明，我们的算法具有良好的泛化能力，优于现有的所有交互式对象选择方法。

##### URL
[https://arxiv.org/abs/1603.04042](https://arxiv.org/abs/1603.04042)

##### PDF
[https://arxiv.org/pdf/1603.04042](https://arxiv.org/pdf/1603.04042)

