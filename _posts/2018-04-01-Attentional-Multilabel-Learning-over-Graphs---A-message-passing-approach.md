---
layout: post
title: "Attentional Multilabel Learning over Graphs - A message passing approach"
date: 2018-04-01 13:01:24
categories: arXiv_AI
tags: arXiv_AI Attention Classification Relation
author: Kien Do, Truyen Tran, Thin Nguyen, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
We address a largely open problem of multilabel classification over graphs. Unlike traditional vector input, a graph has rich variable-size structures, that suggests complex relationships between labels and subgraphs. Uncovering these relations might hold the keys of classification performance and explainability. To this end, we design GAML (Graph Attentional Multi-Label learning), a graph neural network that models the relations present in the input graph, in the label set, and across graph-labels by leveraging the message passing algorithm and attention mechanism. Representation of labels and input nodes is refined iteratively through multiple steps, during which interesting subgraph-label patterns emerge. In addition, GAML is highly flexible by allowing explicit label dependencies to be incorporated easily. It also scales linearly with the number of labels and graph size thanks to our proposed hierarchical attention. These properties open a wide range of applications seen in the real world. We evaluate GAML on an extensive set of experiments with both graph inputs (for predicting drug-protein binding, and drug-cancer response), and classical unstructured inputs. The results are significantly better than well-known multilabel learning techniques.

##### Abstract (translated by Google)
我们解决了一个基于图的多标签分类问题。与传统的矢量输入不同，图形具有丰富的可变尺寸结构，这表明标签和子图之间存在复杂的关系。发现这些关系可能会成为分类表现和可解释性的关键。为此，我们设计了GAML（图注意多标签学习），一种图形神经网络，通过利用消息传递算法和注意机制，对输入图中，标签集中以及图形标签中存在的关系进行建模。标签和输入节点的表示通过多个步骤迭代地改进，在此期间出现有趣的子图标签模式。此外，GAML通过允许将明确的标签依赖性轻松纳入，具有高度的灵活性。由于我们提出的层次关注，它也与标签数量和图形大小成线性关系。这些属性开启了现实世界中广泛的应用。我们对GAML进行了一系列广泛的实验评估，包括图表输入（用于预测药物 - 蛋​​白质结合和药物 - 癌症反应）以及经典的非结构化输入。结果显着优于众所周知的多标签学习技术。

##### URL
[http://arxiv.org/abs/1804.00293](http://arxiv.org/abs/1804.00293)

##### PDF
[http://arxiv.org/pdf/1804.00293](http://arxiv.org/pdf/1804.00293)

