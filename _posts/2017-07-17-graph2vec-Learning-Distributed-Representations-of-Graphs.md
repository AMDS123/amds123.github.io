---
layout: post
title: "graph2vec: Learning Distributed Representations of Graphs"
date: 2017-07-17 05:09:03
categories: arXiv_CL
tags: arXiv_CL Embedding Represenation_Learning Classification
author: Annamalai Narayanan, Mahinthan Chandramohan, Rajasekar Venkatesan, Lihui Chen, Yang Liu, Shantanu Jaiswal
mathjax: true
---

* content
{:toc}

##### Abstract
Recent works on representation learning for graph structured data predominantly focus on learning distributed representations of graph substructures such as nodes and subgraphs. However, many graph analytics tasks such as graph classification and clustering require representing entire graphs as fixed length feature vectors. While the aforementioned approaches are naturally unequipped to learn such representations, graph kernels remain as the most effective way of obtaining them. However, these graph kernels use handcrafted features (e.g., shortest paths, graphlets, etc.) and hence are hampered by problems such as poor generalization. To address this limitation, in this work, we propose a neural embedding framework named graph2vec to learn data-driven distributed representations of arbitrary sized graphs. graph2vec's embeddings are learnt in an unsupervised manner and are task agnostic. Hence, they could be used for any downstream task such as graph classification, clustering and even seeding supervised representation learning approaches. Our experiments on several benchmark and large real-world datasets show that graph2vec achieves significant improvements in classification and clustering accuracies over substructure representation learning approaches and are competitive with state-of-the-art graph kernels.

##### Abstract (translated by Google)
最近关于图形结构化数据表示学习的研究主要集中在学习图形子结构（如节点和子图）的分布式表示。然而，许多图分析任务（如图分类和聚类）要求将整个图表示为固定长度的特征向量。虽然前面提到的方法自然不需要学习这种表示，但是图形内核仍然是获得它们的最有效的方法。然而，这些图形内核使用手工特征（例如，最短路径，图形元素等），因此受到诸如泛化能力差的问题的阻碍。为了解决这个限制，在这项工作中，我们提出了一个名为graph2vec的神经嵌入框架来学习任意大小的图的数据驱动的分布式表示。 graph2vec的嵌入是以无监督的方式学习的，并且是任务不可知的。因此，它们可以用于任何下游任务，如图分类，聚类甚至种子监督表示学习方法。我们在几个基准和大型现实世界的数据集上的实验表明，graph2vec在子结构表示学习方法上实现了分类和聚类精度的显着改进，并且与最先进的图形内核竞争。

##### URL
[https://arxiv.org/abs/1707.05005](https://arxiv.org/abs/1707.05005)

##### PDF
[https://arxiv.org/pdf/1707.05005](https://arxiv.org/pdf/1707.05005)

