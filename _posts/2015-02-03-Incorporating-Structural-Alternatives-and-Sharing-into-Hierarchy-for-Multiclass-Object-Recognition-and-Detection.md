---
layout: post
title: "Incorporating Structural Alternatives and Sharing into Hierarchy for Multiclass Object Recognition and Detection"
date: 2015-02-03 05:45:56
categories: arXiv_CV
tags: arXiv_CV Detection Recognition
author: Xiaolong Wang, Liang Lin, Lichao Huang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a reconfigurable model to recognize and detect multiclass (or multiview) objects with large variation in appearance. Compared with well acknowledged hierarchical models, we study two advanced capabilities in hierarchy for object modeling: (i) "switch" variables(i.e. or-nodes) for specifying alternative compositions, and (ii) making local classifiers (i.e. leaf-nodes) shared among different classes. These capabilities enable us to account well for structural variabilities while preserving the model compact. Our model, in the form of an And-Or Graph, comprises four layers: a batch of leaf-nodes with collaborative edges in bottom for localizing object parts; the or-nodes over bottom to activate their children leaf-nodes; the and-nodes to classify objects as a whole; one root-node on the top for switching multiclass classification, which is also an or-node. For model training, we present an EM-type algorithm, namely dynamical structural optimization (DSO), to iteratively determine the structural configuration, (e.g., leaf-node generation associated with their parent or-nodes and shared across other classes), along with optimizing multi-layer parameters. The proposed method is valid on challenging databases, e.g., PASCAL VOC 2007 and UIUC-People, and it achieves state-of-the-arts performance.

##### Abstract (translated by Google)
本文提出了一种可重构模型来识别和检测外观变化大的多类（或多视点）对象。与公认的分层模型相比，我们研究了对象建模的两个层次结构的高级功能：（i）用于指定替代组合的“开关”变量（即或节点）;（ii）使局部分类器（即叶节点）在不同的班级之间这些功能使我们能够在保持模型紧凑的同时，充分考虑到结构的可变性。我们的模型，以一个And-Or图的形式，包括四个层次：一批叶子节点，底部有合作边，用于定位对象部分;或底部的节点来激活他们的子节点;和 - 节点来将对象分类为整体;顶部的一个根节点用于切换多分类分类，这也是一个or-node。对于模型训练，我们提出了一种EM型算法，即动态结构优化（DSO）来迭代地确定结构配置（例如，与其父节点或与其他类共享的叶节点生成）以及优化多层参数。所提出的方法对具有挑战性的数据库（例如PASCAL VOC 2007和UIUC-People）是有效的，并且它实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1502.00744](https://arxiv.org/abs/1502.00744)

##### PDF
[https://arxiv.org/pdf/1502.00744](https://arxiv.org/pdf/1502.00744)

