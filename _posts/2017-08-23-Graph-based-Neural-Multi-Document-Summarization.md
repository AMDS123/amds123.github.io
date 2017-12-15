---
layout: post
title: "Graph-based Neural Multi-Document Summarization"
date: 2017-08-23 08:46:52
categories: arXiv_CL
tags: arXiv_CL Salient Summarization Embedding CNN RNN Relation
author: Michihiro Yasunaga, Rui Zhang, Kshitijh Meelu, Ayush Pareek, Krishnan Srinivasan, Dragomir Radev
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a neural multi-document summarization (MDS) system that incorporates sentence relation graphs. We employ a Graph Convolutional Network (GCN) on the relation graphs, with sentence embeddings obtained from Recurrent Neural Networks as input node features. Through multiple layer-wise propagation, the GCN generates high-level hidden sentence features for salience estimation. We then use a greedy heuristic to extract salient sentences while avoiding redundancy. In our experiments on DUC 2004, we consider three types of sentence relation graphs and demonstrate the advantage of combining sentence relations in graphs with the representation power of deep neural networks. Our model improves upon traditional graph-based extractive approaches and the vanilla GRU sequence model with no graph, and it achieves competitive results against other state-of-the-art multi-document summarization systems.

##### Abstract (translated by Google)
我们提出了一个结合句子关系图的神经多文档摘要（MDS）系统。我们在关系图上使用图形卷积网络（GCN），将循环神经网络中的句子嵌入作为输入节点特征。通过多层分层传播，GCN为显着性估计生成高级隐藏句子特征。然后，我们使用贪婪的启发式来提取显着的句子，同时避免冗余。在我们对DUC 2004的实验中，我们考虑了三种句子关系图，证明了图中句子关系与深度神经网络表征能力的优点。我们的模型改进了传统的基于图的抽取方法和不含图的vanilla GRU序列模型，并且与其他最先进的多文档摘要系统相比，它获得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1706.06681](https://arxiv.org/abs/1706.06681)

##### PDF
[https://arxiv.org/pdf/1706.06681](https://arxiv.org/pdf/1706.06681)

