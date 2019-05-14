---
layout: post
title: "Dissecting Graph Neural Networks on Graph Classification"
date: 2019-05-11 19:47:19
categories: arXiv_AI
tags: arXiv_AI Attention Classification Prediction
author: Ting Chen, Song Bian, Yizhou Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Graph Neural Nets (GNNs) have received increasing attentions, partially due to their superior performance in many node and graph classification tasks. However, there is a lack of understanding on what they are learning and how sophisticated the learned graph functions are. In this work, we first propose Graph Feature Network (GFN), a simple lightweight neural net defined on a set of graph augmented features. We then propose a dissection of GNNs on graph classification into two parts: 1) the graph filtering, where graph-based neighbor aggregations are performed, and 2) the set function, where a set of hidden node features are composed for prediction. To test the importance of these two parts separately, we prove and leverage the connection that GFN can be derived by linearizing graph filtering part of GNN. Empirically we perform evaluations on common graph classification benchmarks. To our surprise, we find that, despite the simplification, GFN could match or exceed the best accuracies produced by recently proposed GNNs, with a fraction of computation cost. Our results provide new perspectives on both the functions that GNNs learned and the current benchmarks for evaluating them.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04579](http://arxiv.org/abs/1905.04579)

##### PDF
[http://arxiv.org/pdf/1905.04579](http://arxiv.org/pdf/1905.04579)

