---
layout: post
title: "Linking Image and Text with 2-Way Nets"
date: 2017-02-10 20:38:46
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning Relation
author: Aviv Eisenschtat, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
Linking two data sources is a basic building block in numerous computer vision problems. Canonical Correlation Analysis (CCA) achieves this by utilizing a linear optimizer in order to maximize the correlation between the two views. Recent work makes use of non-linear models, including deep learning techniques, that optimize the CCA loss in some feature space. In this paper, we introduce a novel, bi-directional neural network architecture for the task of matching vectors from two data sources. Our approach employs two tied neural network channels that project the two views into a common, maximally correlated space using the Euclidean loss. We show a direct link between the correlation-based loss and Euclidean loss, enabling the use of Euclidean loss for correlation maximization. To overcome common Euclidean regression optimization problems, we modify well-known techniques to our problem, including batch normalization and dropout. We show state of the art results on a number of computer vision matching tasks including MNIST image matching and sentence-image matching on the Flickr8k, Flickr30k and COCO datasets.

##### Abstract (translated by Google)
链接两个数据源是许多计算机视觉问题的基本组成部分。典型相关分析（CCA）通过利用线性优化器来实现这个目的，以最大化两个视图之间的相关性。最近的工作是利用包括深度学习技术的非线性模型来优化某些特征空间中的CCA损失。在本文中，我们介绍了一种新颖的双向神经网络架构，用于从两个数据源中匹配矢量的任务。我们的方法采用两个绑定的神经网络通道，使用欧几里德损失将两个视图投影到一个共同的，最大相关的空间。我们展示了基于相关性的损失和欧几里德损失之间的直接联系，使欧几里德损失的使用相关性最大化。为克服常见的欧几里德回归优化问题，我们修改了众所周知的技术来解决我们的问题，包括批量归一化和丢失。我们在Flickr8k，Flickr30k和COCO数据集上展示了许多计算机视觉匹配任务的最新技术成果，包括MNIST图像匹配和句子图像匹配。

##### URL
[https://arxiv.org/abs/1608.07973](https://arxiv.org/abs/1608.07973)

##### PDF
[https://arxiv.org/pdf/1608.07973](https://arxiv.org/pdf/1608.07973)

