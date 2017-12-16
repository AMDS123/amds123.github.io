---
layout: post
title: "X-CNN: Cross-modal Convolutional Neural Networks for Sparse Datasets"
date: 2016-10-17 14:51:36
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge CNN Gradient_Descent
author: Petar Veličković, Duo Wang, Nicholas D. Lane, Pietro Liò
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose cross-modal convolutional neural networks (X-CNNs), a novel biologically inspired type of CNN architectures, treating gradient descent-specialised CNNs as individual units of processing in a larger-scale network topology, while allowing for unconstrained information flow and/or weight sharing between analogous hidden layers of the network---thus generalising the already well-established concept of neural network ensembles (where information typically may flow only between the output layers of the individual networks). The constituent networks are individually designed to learn the output function on their own subset of the input data, after which cross-connections between them are introduced after each pooling operation to periodically allow for information exchange between them. This injection of knowledge into a model (by prior partition of the input data through domain knowledge or unsupervised methods) is expected to yield greatest returns in sparse data environments, which are typically less suitable for training CNNs. For evaluation purposes, we have compared a standard four-layer CNN as well as a sophisticated FitNet4 architecture against their cross-modal variants on the CIFAR-10 and CIFAR-100 datasets with differing percentages of the training data being removed, and find that at lower levels of data availability, the X-CNNs significantly outperform their baselines (typically providing a 2--6% benefit, depending on the dataset size and whether data augmentation is used), while still maintaining an edge on all of the full dataset tests.

##### Abstract (translated by Google)
在本文中，我们提出了跨模态卷积神经网络（X-CNN），一种新型的生物启发型CNN架构，将梯度下降专用的CNN作为大规模网络拓扑中的单个处理单元处理，同时允许无约束的信息流量和/或权重在网络的类似隐藏层之间共享---因此概括已经完善建立的神经网络集合的概念（其中信息通常可以仅在各个网络的输出层之间流动）。构成网络被单独设计用于在输入数据的自己的子集上学习输出功能，之后在每个汇集操作之后引入它们之间的交叉连接以定期地允许它们之间的信息交换。将知识注入模型（通过对领域知识或无监督方法进行输入数据的事先划分）预期在稀疏数据环境中产生最大的回报，这对于训练CNN是不太适合的。为了评估目的，我们比较了一个标准的四层CNN以及一个复杂的FitNet4体系结构与CIFAR-10和CIFAR-100数据集上的跨模式变体的比较，发现在不同的训练数据被删除的百分比较低的数据可用性水平，X-CNN的性能明显优于基线（取决于数据集的大小以及是否使用数据增强，通常会提供2-6％的收益），同时仍然保持所有全数据集测试的优势。

##### URL
[https://arxiv.org/abs/1610.00163](https://arxiv.org/abs/1610.00163)

##### PDF
[https://arxiv.org/pdf/1610.00163](https://arxiv.org/pdf/1610.00163)

