---
layout: post
title: "Graph2Seq: Graph to Sequence Learning with Attention-based Neural Networks"
date: 2018-05-25 06:13:54
categories: arXiv_AI
tags: arXiv_AI Attention Face Embedding RNN
author: Kun Xu, Lingfei Wu, Zhiguo Wang, Yansong Feng, Michael Witbrock, Vadim Sheinin
mathjax: true
---

* content
{:toc}

##### Abstract
The celebrated \emph{Sequence to Sequence learning (Seq2Seq)} technique and its numerous variants achieve excellent performance on many tasks. However, many machine learning tasks have inputs naturally represented as graphs; existing Seq2Seq models face a significant challenge in achieving accurate conversion from graph form to the appropriate sequence. To address this challenge, we introduce a general end-to-end graph-to-sequence neural encoder-decoder architecture that maps an input graph to a sequence of vectors and uses an attention-based LSTM method to decode the target sequence from these vectors. Our method first generates the node and graph embeddings using an improved graph-based neural network with a novel aggregation strategy to incorporate edge direction information in the node embeddings. We further introduce an attention mechanism that aligns node embeddings and the decoding sequence to better cope with large graphs. Experimental results on bAbI, Shortest Path, and Natural Language Generation tasks demonstrate that our model achieves state-of-the-art performance and significantly outperforms baseline systems; using the proposed aggregation strategy, the model can converge rapidly to the optimal performance.

##### Abstract (translated by Google)
着名的“顺序到序列学习（Seq2Seq）”技术及其众多变体在许多任务中实现了卓越的性能。但是，许多机器学习任务的输入自然表示为图形;现有的Seq2Seq模型在实现从图形形式到适当序列的准确转换方面面临着重大挑战。为了解决这个挑战，我们引入了一个通用的端到端图 - 序列神经编码器 - 解码器架构，将输入图映射到矢量序列，并使用基于注意力的LSTM方法从这些矢量解码目标序列。我们的方法首先使用改进的基于图的神经网络和新的聚合策略生成节点和图嵌入，以将边缘方向信息合并到节点嵌入中。我们进一步引入了一种关注机制，它将节点嵌入和解码序列对齐，以更好地处理大图。 bAbI，最短路径和自然语言生成任务的实验结果表明，我们的模型达到了最先进的性能，并且明显优于基准系统;使用所提出的汇总策略，该模型可以快速收敛到最佳性能。

##### URL
[http://arxiv.org/abs/1804.00823](http://arxiv.org/abs/1804.00823)

##### PDF
[http://arxiv.org/pdf/1804.00823](http://arxiv.org/pdf/1804.00823)

