---
layout: post
title: "Graph Attention Networks"
date: 2017-12-20 11:18:15
categories: arXiv_AI
tags: arXiv_AI Attention
author: Petar Veli&#x10d;kovi&#x107;, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Li&#xf2;, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We present graph attention networks (GATs), novel neural network architectures that operate on graph-structured data, leveraging masked self-attentional layers to address the shortcomings of prior methods based on graph convolutions or their approximations. By stacking layers in which nodes are able to attend over their neighborhoods' features, we enable (implicitly) specifying different weights to different nodes in a neighborhood, without requiring any kind of costly matrix operation (such as inversion) or depending on knowing the graph structure upfront. In this way, we address several key challenges of spectral-based graph neural networks simultaneously, and make our model readily applicable to inductive as well as transductive problems. Our GAT models have achieved or matched state-of-the-art results across four established transductive and inductive graph benchmarks: the Cora, Citeseer and Pubmed citation network datasets, as well as a protein-protein interaction dataset (wherein test graphs remain unseen during training).

##### Abstract (translated by Google)
我们提出了图形关注网络（GAT），一种新的神经网络架构，它运行在图形结构化的数据上，利用掩蔽的自我注意层来解决基于图形卷积或其近似的现有方法的缺点。通过堆叠节点能够参与其邻域特征的层，我们启用（隐含地）为邻居中的不同节点指定不同的权重，而不需要任何类型的昂贵的矩阵运算（例如反演）或者依赖于知道图结构前期。这样，我们同时解决了基于谱图的神经网络的几个关键挑战，并且使我们的模型容易适用于归纳和转换问题。我们的GAT模型已经通过四个已建立的直导和归纳图谱基准（Cora，Citeseer和Pubmed引文网络数据集）以及一个蛋白质 - 蛋白质相互作用数据集（其中测试图在过程中不被看见）达到或匹配了最新的结果训练）。

##### URL
[http://arxiv.org/abs/1710.10903](http://arxiv.org/abs/1710.10903)

##### PDF
[http://arxiv.org/pdf/1710.10903](http://arxiv.org/pdf/1710.10903)

