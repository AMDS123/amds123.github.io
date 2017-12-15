---
layout: post
title: "Bidirectional Tree-Structured LSTM with Head Lexicalization"
date: 2016-11-21 14:01:53
categories: arXiv_CL
tags: arXiv_CL Sentiment RNN Classification
author: Zhiyang Teng, Yue Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Sequential LSTM has been extended to model tree structures, giving competitive results for a number of tasks. Existing methods model constituent trees by bottom-up combinations of constituent nodes, making direct use of input word information only for leaf nodes. This is different from sequential LSTMs, which contain reference to input words for each node. In this paper, we propose a method for automatic head-lexicalization for tree-structure LSTMs, propagating head words from leaf nodes to every constituent node. In addition, enabled by head lexicalization, we build a tree LSTM in the top-down direction, which corresponds to bidirectional sequential LSTM structurally. Experiments show that both extensions give better representations of tree structures. Our final model gives the best results on the Standford Sentiment Treebank and highly competitive results on the TREC question type classification task.

##### Abstract (translated by Google)
顺序LSTM已经扩展到模型树结构，为许多任务提供了有竞争力的结果。现有方法通过构成节点的自底向上组合来对组成树进行建模，使得仅对叶节点直接使用输入字信息。这与顺序LSTM不同，后者包含对每个节点的输入字的引用。在本文中，我们提出了一种树形结构LSTM的自动头词汇化方法，将叶节点的头词传播到每个结构节点。另外，通过头词汇化，我们在上下方向建立树LSTM，这在结构上对应于双向顺序LSTM。实验表明，这两个扩展给树结构更好的表示。我们的最终模型在斯坦福情绪树状图上给出了最好的结果，并在TREC问题类型分类任务上给出了高度竞争的结果。

##### URL
[https://arxiv.org/abs/1611.06788](https://arxiv.org/abs/1611.06788)

##### PDF
[https://arxiv.org/pdf/1611.06788](https://arxiv.org/pdf/1611.06788)

