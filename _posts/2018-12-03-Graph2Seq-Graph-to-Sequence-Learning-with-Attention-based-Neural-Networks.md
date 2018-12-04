---
layout: post
title: "Graph2Seq: Graph to Sequence Learning with Attention-based Neural Networks"
date: 2018-12-03 16:43:37
categories: arXiv_AI
tags: arXiv_AI Attention Face Embedding RNN
author: Kun Xu, Lingfei Wu, Zhiguo Wang, Yansong Feng, Michael Witbrock, Vadim Sheinin
mathjax: true
---

* content
{:toc}

##### Abstract
The celebrated Sequence to Sequence learning (Seq2Seq) technique and its numerous variants achieve excellent performance on many tasks. However, many machine learning tasks have inputs naturally represented as graphs; existing Seq2Seq models face a significant challenge in achieving accurate conversion from graph form to the appropriate sequence. To address this challenge, we introduce a novel general end-to-end graph-to-sequence neural encoder-decoder model that maps an input graph to a sequence of vectors and uses an attention-based LSTM method to decode the target sequence from these vectors. Our method first generates the node and graph embeddings using an improved graph-based neural network with a novel aggregation strategy to incorporate edge direction information in the node embeddings. We further introduce an attention mechanism that aligns node embeddings and the decoding sequence to better cope with large graphs. Experimental results on bAbI, Shortest Path, and Natural Language Generation tasks demonstrate that our model achieves state-of-the-art performance and significantly outperforms existing graph neural networks, Seq2Seq, and Tree2Seq models; using the proposed bi-directional node embedding aggregation strategy, the model can converge rapidly to the optimal performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.00823](http://arxiv.org/abs/1804.00823)

##### PDF
[http://arxiv.org/pdf/1804.00823](http://arxiv.org/pdf/1804.00823)

