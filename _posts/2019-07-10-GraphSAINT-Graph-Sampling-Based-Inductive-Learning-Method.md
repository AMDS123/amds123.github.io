---
layout: post
title: "GraphSAINT: Graph Sampling Based Inductive Learning Method"
date: 2019-07-10 21:11:13
categories: arXiv_AI
tags: arXiv_AI CNN
author: Hanqing Zeng, Hongkuan Zhou, Ajitesh Srivastava, Rajgopal Kannan, Viktor Prasanna
mathjax: true
---

* content
{:toc}

##### Abstract
Graph Convolutional Networks (GCNs) are powerful models for learning representations of attributed graphs.To scale GCNs to large graphs, state-of-the-art methods use various layer sampling techniques to alleviate the "neighbor explosion" problem during minibatch training. Here we proposeGraphSAINT, a graph sampling based inductive learning method that improves training efficiency in a fundamentally different way. By a change of perspective, GraphSAINT constructs minibatches by sampling the training graph, rather than the nodes or edges across GCN layers. Each iteration, a complete GCN is built from the properly sampled subgraph. Thus, we ensure fixed number of well-connected nodes in all layers. We further propose normalization technique to eliminate bias, and sampling algorithms for variance reduction. Importantly, we can decouple the sampling process from the forward and backward propagation of training, and extend GraphSAINT with other graph samplers and GCN variants. Comparing with strong baselines using layer sampling, GraphSAINT demonstrates superior performance in both accuracy and training time on four large graphs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04931](http://arxiv.org/abs/1907.04931)

##### PDF
[http://arxiv.org/pdf/1907.04931](http://arxiv.org/pdf/1907.04931)

