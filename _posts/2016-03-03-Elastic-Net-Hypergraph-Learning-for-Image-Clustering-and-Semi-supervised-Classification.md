---
layout: post
title: "Elastic Net Hypergraph Learning for Image Clustering and Semi-supervised Classification"
date: 2016-03-03 13:37:23
categories: arXiv_CV
tags: arXiv_CV Sparse Face Classification Relation
author: Qingshan Liu, Yubao Sun, Cantian Wang, Tongliang Liu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Graph model is emerging as a very effective tool for learning the complex structures and relationships hidden in data. Generally, the critical purpose of graph-oriented learning algorithms is to construct an informative graph for image clustering and classification tasks. In addition to the classical $K$-nearest-neighbor and $r$-neighborhood methods for graph construction, $l_1$-graph and its variants are emerging methods for finding the neighboring samples of a center datum, where the corresponding ingoing edge weights are simultaneously derived by the sparse reconstruction coefficients of the remaining samples. However, the pair-wise links of $l_1$-graph are not capable of capturing the high order relationships between the center datum and its prominent data in sparse reconstruction. Meanwhile, from the perspective of variable selection, the $l_1$ norm sparse constraint, regarded as a LASSO model, tends to select only one datum from a group of data that are highly correlated and ignore the others. To simultaneously cope with these drawbacks, we propose a new elastic net hypergraph learning model, which consists of two steps. In the first step, the Robust Matrix Elastic Net model is constructed to find the canonically related samples in a somewhat greedy way, achieving the grouping effect by adding the $l_2$ penalty to the $l_1$ constraint. In the second step, hypergraph is used to represent the high order relationships between each datum and its prominent samples by regarding them as a hyperedge. Subsequently, hypergraph Laplacian matrix is constructed for further analysis. New hypergraph learning algorithms, including unsupervised clustering and multi-class semi-supervised classification, are then derived. Extensive experiments on face and handwriting databases demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)
图模型正在成为学习隐藏在数据中的复杂结构和关系的非常有效的工具。一般而言，面向图学习算法的关键目的是为图像聚类和分类任务构建信息图。除了经典的$ K $ -nearest-neighbor和$ r $ -neighborhood方法用于图构造之外，$ l_1 $ -graph及其变体是用于找到中心数据的相邻样本的新兴方法，其中相应的进入边权重同时由剩余样本的稀疏重建系数导出。然而，$ l_1 $ -graph的成对链接不能捕获中心数据与其稀疏重构中的突出数据之间的高阶关系。同时，从变量选择的角度来看，作为LASSO模型的$ l_1 $范数稀疏约束往往只从一组数据中选择一个数据高度相关，忽略其他数据。为了同时处理这些缺陷，我们提出了一个新的弹性网络超图学习模型，它由两个步骤组成。在第一步中，Robust Matrix Elastic Net模型被构造成以某种有点贪婪的方式找到典型相关的样本，通过将$ l_2 $惩罚加入$ l_1 $约束来实现分组效果。在第二步中，超图用来表示每个数据与其突出样本之间的高阶关系，并将它们视为一个超边。随后，超图拉普拉斯矩阵被构造用于进一步分析。然后导出新的超图学习算法，包括无监督聚类和多类半监督分类。在面部和手写数据库上的大量实验证明了所提出方法的有效性。

##### URL
[https://arxiv.org/abs/1603.01096](https://arxiv.org/abs/1603.01096)

##### PDF
[https://arxiv.org/pdf/1603.01096](https://arxiv.org/pdf/1603.01096)

