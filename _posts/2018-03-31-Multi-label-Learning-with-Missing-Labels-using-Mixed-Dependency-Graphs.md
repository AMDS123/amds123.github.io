---
layout: post
title: "Multi-label Learning with Missing Labels using Mixed Dependency Graphs"
date: 2018-03-31 04:15:11
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Sparse
author: Baoyuan Wu, Fan Jia, Wei Liu, Bernard Ghanem, Siwei Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
This work focuses on the problem of multi-label learning with missing labels (MLML), which aims to label each test instance with multiple class labels given training instances that have an incomplete/partial set of these labels. The key point to handle missing labels is propagating the label information from provided labels to missing labels, through a dependency graph that each label of each instance is treated as a node. We build this graph by utilizing different types of label dependencies. Specifically, the instance-level similarity is served as undirected edges to connect the label nodes across different instances and the semantic label hierarchy is used as directed edges to connect different classes. This base graph is referred to as the mixed dependency graph, as it includes both undirected and directed edges. Furthermore, we present another two types of label dependencies to connect the label nodes across different classes. One is the class co-occurrence, which is also encoded as undirected edges. Combining with the base graph, we obtain a new mixed graph, called MG-CO (mixed graph with co-occurrence). The other is the sparse and low rank decomposition of the whole label matrix, to embed high-order dependencies over all labels. Combining with the base graph, the new mixed graph is called as MG-SL (mixed graph with sparse and low rank decomposition). Based on MG-CO and MG-SL, we propose two convex transductive formulations of the MLML problem, denoted as MLMG-CO and MLMG-SL, respectively. Two important applications, including image annotation and tag based image retrieval, can be jointly handled using our proposed methods. Experiments on benchmark datasets show that our methods give significant improvements in performance and robustness to missing labels over the state-of-the-art methods.

##### Abstract (translated by Google)
这项工作主要关注带有缺失标签（MLML）的多标签学习问题，该标签旨在给每个测试实例添加多个类标签，给定具有这些标签的不完整/部分集合的培训实例。处理缺失标签的关键点是通过依赖图将标签信息从提供的标签传播到缺失标签，每个实例的每个标签都被视为一个节点。我们通过利用不同类型的标签依赖性来构建此图。具体而言，实例级别的相似性用作无向边，以跨不同实例连接标签节点，而语义标签层次结构用作有向边来连接不同类。这个基本图被称为混合依赖图，因为它包括无向和有向边。此外，我们还介绍了另外两种类型的标签依赖性来连接跨不同类的标签节点。一类是类同现，它也被编码为无向边。结合基本图，我们获得了一个新的混合图，称为MG-CO（具有共现的混合图）。另一个是整个标签矩阵的稀疏和低秩分解，以在所有标签上嵌入高阶依赖关系。结合基本图，新的混合图被称为MG-SL（具有稀疏和低等级分解的混合图）。基于MG-CO和MG-SL，我们提出了两种MLML问题的凸函数式，分别表示为MLMG-CO和MLMG-SL。可以使用我们提出的方法联合处理两个重要应用，包括图像标注和基于标签的图像检索。基准数据集上的实验表明，我们的方法在性能和鲁棒性方面显着提高了缺失标签的水平。

##### URL
[http://arxiv.org/abs/1804.00117](http://arxiv.org/abs/1804.00117)

##### PDF
[http://arxiv.org/pdf/1804.00117](http://arxiv.org/pdf/1804.00117)

