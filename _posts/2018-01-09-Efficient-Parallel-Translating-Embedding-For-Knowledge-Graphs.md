---
layout: post
title: "Efficient Parallel Translating Embedding For Knowledge Graphs"
date: 2018-01-09 02:40:30
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding Relation
author: Denghui Zhang, Manling Li, Yantao Jia, Yuanzhuo Wang, Xueqi Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge graph embedding aims to embed entities and relations of knowledge graphs into low-dimensional vector spaces. Translating embedding methods regard relations as the translation from head entities to tail entities, which achieve the state-of-the-art results among knowledge graph embedding methods. However, a major limitation of these methods is the time consuming training process, which may take several days or even weeks for large knowledge graphs, and result in great difficulty in practical applications. In this paper, we propose an efficient parallel framework for translating embedding methods, called ParTrans-X, which enables the methods to be paralleled without locks by utilizing the distinguished structures of knowledge graphs. Experiments on two datasets with three typical translating embedding methods, i.e., TransE [3], TransH [17], and a more efficient variant TransE- AdaGrad [10] validate that ParTrans-X can speed up the training process by more than an order of magnitude.

##### Abstract (translated by Google)
知识图嵌入的目的是将知识图的实体和关系嵌入到低维向量空间中。将嵌入方法转化为关系作为从头实体到尾实体的转换，实现了知识图嵌入方法中的最新成果。然而，这些方法的一个主要局限是耗时的培训过程，对于大型的知识图可能需要几天甚至几周的时间，并且在实际应用中造成很大的困难。在本文中，我们提出了一个高效的翻译嵌入方法的并行框架，称为ParTrans-X，通过利用知识图的显着结构，使得方法可以无锁并联。两个数据集上的TransE [3]，TransH [17]和一个更有效的变种TransE-AdaGrad [10]的两个数据集的实验验证了ParTrans-X可以加速训练过程不止一个命令数量级。

##### URL
[http://arxiv.org/abs/1703.10316](http://arxiv.org/abs/1703.10316)

##### PDF
[http://arxiv.org/pdf/1703.10316](http://arxiv.org/pdf/1703.10316)

