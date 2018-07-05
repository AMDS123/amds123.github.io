---
layout: post
title: "Non-Local Graph Convolutional Networks for Skeleton-Based Action Recognition"
date: 2018-07-04 00:50:14
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Recognition
author: Lei Shi, Yifan Zhang, Jian Cheng, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional deep methods for skeleton-based action recognition usually structure the skeleton as a coordinates sequence or a pseudo-image to feed to RNNs or CNNs, which cannot explicitly exploit the natural connectivity among the joints. Recently, graph convolutional networks (GCNs), which generalize CNNs to more generic non-Euclidean structures, obtains remarkable performance for skeleton-based action recognition. However, the topology of the graph is set by hand and fixed over all layers, which may be not optimal for the action recognition task and the hierarchical CNN structures. Besides, the first-order information (the coordinate of joints) is mainly used in former GCNs, while the second-order information (the length and direction of bones) is less exploited. In this work, a novel two-stream nonlocal graph convolutional network is proposed to solve these problems. The topology of the graph in each layer of the model can be either uniformly or individually learned by BP algorithm, which brings more flexibility and generality. Meanwhile, a two-stream framework is proposed to model both of the joints and bones information simultaneously, which further boost the recognition performance. Extensive experiments on two large-scale datasets, NTU-RGB+D and Kinetics, demonstrate the performance of our model exceeds the state-of-the-art by a significant margin.

##### Abstract (translated by Google)
用于基于骨架的动作识别的传统深度方法通常将骨架构造为坐标序列或伪图像以馈送到RNN或CNN，其不能明确地利用关节之间的自然连接。最近，图形卷积网络（GCN）将CNN推广到更通用的非欧几里德结构，为基于骨架的动作识别获得了显着的性能。然而，图的拓扑是手动设置的并且固定在所有层上，这对于动作识别任务和分层CNN结构可能不是最佳的。此外，一阶信息（关节的坐标）主要用于以前的GCN，而二阶信息（骨骼的长度和方向）较少被利用。在这项工作中，提出了一种新的双流非局部图卷积网络来解决这些问题。模型的每一层中的图形拓扑可以通过BP算法统一或单独学习，这带来了更大的灵活性和通用性。同时，提出了一种双流框架来同时对关节和骨骼信息进行建模，进一步提高了识别性能。对两个大型数据集NTU-RGB + D和Kinetics的广泛实验证明，我们的模型的性能超过了现有技术的显着水平。

##### URL
[http://arxiv.org/abs/1805.07694](http://arxiv.org/abs/1805.07694)

##### PDF
[http://arxiv.org/pdf/1805.07694](http://arxiv.org/pdf/1805.07694)

