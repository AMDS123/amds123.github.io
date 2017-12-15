---
layout: post
title: "Towards Building Deep Networks with Bayesian Factor Graphs"
date: 2015-02-16 11:01:25
categories: arXiv_CV
tags: arXiv_CV Knowledge Inference Classification
author: Amedeo Buonanno, Francesco A.N. Palmieri
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Multi-Layer Network based on the Bayesian framework of the Factor Graphs in Reduced Normal Form (FGrn) applied to a two-dimensional lattice. The Latent Variable Model (LVM) is the basic building block of a quadtree hierarchy built on top of a bottom layer of random variables that represent pixels of an image, a feature map, or more generally a collection of spatially distributed discrete variables. The multi-layer architecture implements a hierarchical data representation that, via belief propagation, can be used for learning and inference. Typical uses are pattern completion, correction and classification. The FGrn paradigm provides great flexibility and modularity and appears as a promising candidate for building deep networks: the system can be easily extended by introducing new and different (in cardinality and in type) variables. Prior knowledge, or supervised information, can be introduced at different scales. The FGrn paradigm provides a handy way for building all kinds of architectures by interconnecting only three types of units: Single Input Single Output (SISO) blocks, Sources and Replicators. The network is designed like a circuit diagram and the belief messages flow bidirectionally in the whole system. The learning algorithms operate only locally within each block. The framework is demonstrated in this paper in a three-layer structure applied to images extracted from a standard data set.

##### Abstract (translated by Google)
我们提出了一个基于贝叶斯框架的应用于二维点阵的归约规范形式（FGrn）的多层网络。潜在变量模型（LVM）是构建在随机变量的底层之上的四叉树分层结构的基本构建模块，所述随机变量表示图像的像素，特征映射或者更一般地是空间分布的离散变量的集合。多层体系结构实现了分层数据表示，通过置信传播，可以用于学习和推理。典型的用途是模式完成，校正和分类。 FGrn范式提供了极大的灵活性和模块性，并且似乎是建立深度网络的有希望的候选者：通过引入新的和不同的（基数和类型）变量，系统可以容易地扩展。先前的知识或监督的信息可以在不同的尺度上引入。 FGrn范例为构建各种架构提供了一种便捷的方法，只需将三种类型的单元互连：单输入单输出（SISO）模块，信号源和复制器。网络被设计成一个电路图，信息消息在整个系统中双向流动。学习算法仅在每个块内本地操作。该框架在本文中以三层结构应用于从标准数据集中提取的图像进行演示。

##### URL
[https://arxiv.org/abs/1502.04492](https://arxiv.org/abs/1502.04492)

##### PDF
[https://arxiv.org/pdf/1502.04492](https://arxiv.org/pdf/1502.04492)

