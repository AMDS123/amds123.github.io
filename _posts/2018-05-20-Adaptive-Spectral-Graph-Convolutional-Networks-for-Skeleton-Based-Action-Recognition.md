---
layout: post
title: "Adaptive Spectral Graph Convolutional Networks for Skeleton-Based Action Recognition"
date: 2018-05-20 02:48:38
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Recognition
author: Lei Shi, Yifan Zhang, Jian Cheng, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional deep methods for skeleton-based action recognition usually structure the skeleton as a coordinates sequence or a pseudo-image to feed to RNNs or CNNs, which cannot explicitly exploit the natural connectivity among the joints. Recently, graph convolutional networks (GCNs), which generalize CNNs to more generic non-Euclidean structures, obtains remarkable performance for skeleton-based action recognition. In this work, we propose a novel adaptive spectral graph convolutional network which address the three major issues exposed in former GCN-based methods applied to action recognition: 1) The sampling function of graph convolutional operation applied in former methods is usually heuristically designed. We avoid the tricked definition of sampling function by transforming the GCN to frequency domain based on spectral graph theory. 2) The topology of the graph is set by hand and fixed over all layers, which may be not optimal for the action recognition task and the hierarchical CNN structures. In our model, the topology of the graph in each layer can be either uniformly or individually learned by BP algorithm, which can bring more flexibility and generality. 3) The first-order information (the coordinate of joints) is mainly used in former GCNs, while the second-order information (the length and direction of bones) is less exploited. A two-stream framework is proposed in this work to model both of the joints and bones information simultaneously. Extensive experiments on two large-scale datasets, NTU-RGB+D and Kinetics, demonstrate the performance of our model exceeds the state-of-the-art by a significant margin.

##### Abstract (translated by Google)
传统的基于骨架动作识别的深层方法通常将骨架构造为坐标序列或伪图像以馈送给RNN或CNN，其不能明确地利用关节之间的自然连接。最近，将CNN推广到更通用的非欧几里德结构的图形卷积网络（GCN）获得了基于骨架动作识别的卓越性能。在这项工作中，我们提出了一种新颖的自适应谱图卷积网络，它解决了以前基于GCN的方法应用于动作识别的三个主要问题：1）在前一种方法中应用的图形卷积运算的采样函数通常是启发式设计的。我们通过基于谱图理论将GCN转换到频域来避免采样函数的欺骗定义。 2）图的拓扑结构是手动设置的，并固定在所有层上，这可能不是动作识别任务和层次CNN结构的最佳选择。在我们的模型中，每层图的拓扑结构可以通过BP算法统一或单独学习，这可以带来更大的灵活性和通用性。 3）一阶信息（关节坐标）主要用于原GCNs，而二阶信息（骨骼的长度和方向）较少被利用。在这项工作中提出了一个双流框架来同时建模关节和骨骼信息。在两个大型数据集NTU-RGB + D和Kinetics上进行的大量实验证明，我们的模型的性能超过了现有技术的显着水平。

##### URL
[https://arxiv.org/abs/1805.07694](https://arxiv.org/abs/1805.07694)

##### PDF
[https://arxiv.org/pdf/1805.07694](https://arxiv.org/pdf/1805.07694)

