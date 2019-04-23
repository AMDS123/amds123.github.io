---
layout: post
title: "DDGK: Learning Graph Representations for Deep Divergence Graph Kernels"
date: 2019-04-21 22:45:04
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention Embedding Classification Prediction
author: Rami Al-Rfou, Dustin Zelle, Bryan Perozzi
mathjax: true
---

* content
{:toc}

##### Abstract
Can neural networks learn to compare graphs without feature engineering? In this paper, we show that it is possible to learn representations for graph similarity with neither domain knowledge nor supervision (i.e.\ feature engineering or labeled graphs). We propose Deep Divergence Graph Kernels, an unsupervised method for learning representations over graphs that encodes a relaxed notion of graph isomorphism. Our method consists of three parts. First, we learn an encoder for each anchor graph to capture its structure. Second, for each pair of graphs, we train a cross-graph attention network which uses the node representations of an anchor graph to reconstruct another graph. This approach, which we call isomorphism attention, captures how well the representations of one graph can encode another. We use the attention-augmented encoder's predictions to define a divergence score for each pair of graphs. Finally, we construct an embedding space for all graphs using these pair-wise divergence scores. 
 Unlike previous work, much of which relies on 1) supervision, 2) domain specific knowledge (e.g. a reliance on Weisfeiler-Lehman kernels), and 3) known node alignment, our unsupervised method jointly learns node representations, graph representations, and an attention-based alignment between graphs. 
 Our experimental results show that Deep Divergence Graph Kernels can learn an unsupervised alignment between graphs, and that the learned representations achieve competitive results when used as features on a number of challenging graph classification tasks. Furthermore, we illustrate how the learned attention allows insight into the the alignment of sub-structures across graphs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09671](http://arxiv.org/abs/1904.09671)

##### PDF
[http://arxiv.org/pdf/1904.09671](http://arxiv.org/pdf/1904.09671)

