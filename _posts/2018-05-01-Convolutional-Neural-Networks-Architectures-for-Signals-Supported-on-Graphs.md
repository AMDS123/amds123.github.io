---
layout: post
title: "Convolutional Neural Networks Architectures for Signals Supported on Graphs"
date: 2018-05-01 03:04:31
categories: arXiv_AI
tags: arXiv_AI CNN Classification
author: Fernando Gama, Antonio G. Marques, Geert Leus, Alejandro Ribeiro
mathjax: true
---

* content
{:toc}

##### Abstract
We describe two architectures that generalize convolutional neural networks (CNNs) for the processing of signals supported on graphs. The selection graph neural network (GNN) replaces linear time invariant filters with linear shift invariant graph filters to generate convolutional features and reinterprets pooling as a possibly nonlinear subsampling stage where nearby nodes pool their information in a set of preselected sample nodes. A key component of the architecture is to remember the position of sampled nodes to permit computation of convolutional features at deeper layers. The aggregation GNN diffuses the signal through the graph and stores the sequence of diffused components observed by a designated node. This procedure effectively aggregates all components into a stream of information having temporal structure to which the convolution and pooling stages of regular CNNs can be applied. A multinode version of aggregation GNNs is further introduced for operation in large scale graphs. An important property of selection and aggregation GNNs is that they reduce to conventional CNNs when particularized to time signals reinterpreted as graph signals in a circulant graph. Comparative numerical analyses are performed in a synthetic source localization application. Performance is evaluated for a text category classification problem using word proximity networks. Multinode aggregation GNNs are consistently the best performing GNN architecture.

##### Abstract (translated by Google)
我们描述了两种架构，将卷积神经网络（CNN）推广用于处理图上支持的信号。选择图神经网络（GNN）用线性移位不变图滤波器代替线性时不变滤波器来生成卷积特征，并将池重新解释为可能的非线性子采样阶段，其中附近的节点将它们的信息汇集在一组预先选择的采样节点中。该体系结构的一个关键组成部分是记住采样节点的位置，以允许计算更深层的卷积特征。聚合GNN通过图扩散信号并存储由指定节点观察到的扩散分量序列。该过程有效地将所有组件集合成具有时间结构的信息流，常规CNN的卷积和汇集阶段可以应用于该时间结构。进一步引入了聚集GNN的多节点版本以用于大规模图中的操作。选择和聚合GNNs的一个重要特性是，它们将特定时间信号重新解释为循环图中的图形信号时，它们还原为常规CNN。比较性数值分析在合成源定位应用中进行。针对使用词邻近网络的文本类别分类问题评估性能。多节点聚合GNN始终是性能最好的GNN体系结构。

##### URL
[https://arxiv.org/abs/1805.00165](https://arxiv.org/abs/1805.00165)

##### PDF
[https://arxiv.org/pdf/1805.00165](https://arxiv.org/pdf/1805.00165)

