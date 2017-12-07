---
layout: post
title: "Discriminatively Trained And-Or Graph Models for Object Shape Detection"
date: 2015-02-02 02:04:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Recognition
author: Liang Lin, Xiaolong Wang, Wei Yang, Jian-Huang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate a novel reconfigurable part-based model, namely And-Or graph model, to recognize object shapes in images. Our proposed model consists of four layers: leaf-nodes at the bottom are local classifiers for detecting contour fragments; or-nodes above the leaf-nodes function as the switches to activate their child leaf-nodes, making the model reconfigurable during inference; and-nodes in a higher layer capture holistic shape deformations; one root-node on the top, which is also an or-node, activates one of its child and-nodes to deal with large global variations (e.g. different poses and views). We propose a novel structural optimization algorithm to discriminatively train the And-Or model from weakly annotated data. This algorithm iteratively determines the model structures (e.g. the nodes and their layouts) along with the parameter learning. On several challenging datasets, our model demonstrates the effectiveness to perform robust shape-based object detection against background clutter and outperforms the other state-of-the-art approaches. We also release a new shape database with annotations, which includes more than 1500 challenging shape instances, for recognition and detection.

##### Abstract (translated by Google)
在本文中，我们研究了一种新的可重构零件模型，即And-Or图模型来识别图像中的物体形状。我们提出的模型由四层组成：底部的叶节点是检测轮廓片段的局部分类器;或者叶子节点之上的节点作为交换机来激活它们的子叶节点，使得模型在推理期间可重新配置;并在更高层节点捕捉整体形状变形;顶部的一个根节点，也是一个or-node，激活它的一个子节点来处理大的全局变化（例如不同的姿势和视图）。我们提出了一种新的结构优化算法，从弱注释数据中区分地训练And-Or模型。该算法连同参数学习一起迭代地确定模型结构（例如节点及其布局）。在一些具有挑战性的数据集上，我们的模型演示了对背景混乱执行鲁棒的基于形状的对象检测的有效性，并且胜过了其他最先进的方法。我们还发布了带有注释的新形状数据库，其中包括1500多个具有挑战性的形状实例，用于识别和检测。

##### URL
[https://arxiv.org/abs/1502.00341](https://arxiv.org/abs/1502.00341)

##### PDF
[https://arxiv.org/pdf/1502.00341](https://arxiv.org/pdf/1502.00341)

