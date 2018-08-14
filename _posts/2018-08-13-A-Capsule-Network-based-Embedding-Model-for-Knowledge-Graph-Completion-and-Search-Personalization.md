---
layout: post
title: "A Capsule Network-based Embedding Model for Knowledge Graph Completion and Search Personalization"
date: 2018-08-13 09:35:44
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge Embedding Prediction Relation
author: Dai Quoc Nguyen, Thanh Vu, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Phung
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce an embedding model, named CapsE, exploring a capsule network to model relationship triples \textit{(subject, relation, object)}. Our CapsE represents each triple as a 3-column matrix where each column vector represents the embedding of an element in the triple. This 3-column matrix is then fed to a convolution layer where multiple filters are operated to generate different feature maps. These feature maps are used to construct capsules in the first capsule layer. Capsule layers are connected via dynamic routing mechanism. The last capsule layer consists of only one capsule to produce a vector output. The length of this vector output is used to measure the plausibility of the triple. Our proposed CapsE obtains state-of-the-art link prediction results for knowledge graph completion on two benchmark datasets: WN18RR and FB15k-237, and outperforms strong search personalization baselines on SEARCH17 dataset.

##### Abstract (translated by Google)
在本文中，我们介绍了一个名为CapsE的嵌入模型，探索一个胶囊网络来建模关系三元组\ textit {（subject，relation，object）}。我们的CapsE将每个三元组表示为3列矩阵，其中每个列向量表示元素在三元组中的嵌入。然后将该3列矩阵馈送到卷积层，其中操作多个滤波器以生成不同的特征映射。这些特征图用于在第一胶囊层中构建胶囊。胶囊层通过动态路由机制连接。最后一个胶囊层仅由一个胶囊组成，以产生矢量输出。该向量输出的长度用于测量三元组的合理性。我们提出的CapsE在两个基准数据集上获得了知识图完成的最新链接预测结果：WN18RR和FB15k-237，并且优于SEARCH17数据集上的强搜索个性化基线。

##### URL
[http://arxiv.org/abs/1808.04122](http://arxiv.org/abs/1808.04122)

##### PDF
[http://arxiv.org/pdf/1808.04122](http://arxiv.org/pdf/1808.04122)

