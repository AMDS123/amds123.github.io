---
layout: post
title: "Learning Contour-Fragment-based Shape Model with And-Or Tree Representation"
date: 2015-02-03 03:42:10
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization Inference Detection
author: Liang Lin, Xiaolong Wang, Wei Yang, Jianhuang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a simple yet effective method to learn the hierarchical object shape model consisting of local contour fragments, which represents a category of shapes in the form of an And-Or tree. This model extends the traditional hierarchical tree structures by introducing the "switch" variables (i.e. the or-nodes) that explicitly specify production rules to capture shape variations. We thus define the model with three layers: the leaf-nodes for detecting local contour fragments, the or-nodes specifying selection of leaf-nodes, and the root-node encoding the holistic distortion. In the training stage, for optimization of the And-Or tree learning, we extend the concave-convex procedure (CCCP) by embedding the structural clustering during the iterative learning steps. The inference of shape detection is consistent with the model optimization, which integrates the local testings via the leaf-nodes and or-nodes with the global verification via the root-node. The advantages of our approach are validated on the challenging shape databases (i.e., ETHZ and INRIA Horse) and summarized as follows. (1) The proposed method is able to accurately localize shape contours against unreliable edge detection and edge tracing. (2) The And-Or tree model enables us to well capture the intraclass variance.

##### Abstract (translated by Google)
本文提出了一种简单而有效的方法来学习由局部轮廓片段组成的分层对象形状模型，该模型以And-Or树形式表示一个形状类别。该模型通过引入显式指定生产规则以捕获形状变化的“开关”变量（即，或节点）来扩展传统的分层树结构。因此，我们定义了三层模型：用于检测局部轮廓片段的叶节点，指定叶节点选择的节点，以及编码整体变形的根节点。在训练阶段，为了优化And-Or树学习，我们通过在迭代学习步骤中嵌入结构聚类来扩展凹凸过程（CCCP）。形状检测的推理与模型优化相一致，模型优化通过叶节点和或节点将本地测试与通过根节点的全局验证相结合。我们的方法的优点是在具有挑战性的形状数据库（即ETHZ和INRIA Horse）上进行验证，总结如下。 （1）提出的方法能够准确定位形状轮廓不可靠的边缘检测和边缘跟踪。 （2）And-Or树模型使我们能很好地捕捉到组内方差。

##### URL
[https://arxiv.org/abs/1502.00723](https://arxiv.org/abs/1502.00723)

##### PDF
[https://arxiv.org/pdf/1502.00723](https://arxiv.org/pdf/1502.00723)

