---
layout: post
title: "Convolutional Neural Network Architectures for Signals Supported on Graphs"
date: 2018-12-07 01:17:25
categories: arXiv_AI
tags: arXiv_AI CNN Classification
author: Fernando Gama, Antonio G. Marques, Geert Leus, Alejandro Ribeiro
mathjax: true
---

* content
{:toc}

##### Abstract
Two architectures that generalize convolutional neural networks (CNNs) for the processing of signals supported on graphs are introduced. We start with the selection graph neural network (GNN), which replaces linear time invariant filters with linear shift invariant graph filters to generate convolutional features and reinterprets pooling as a possibly nonlinear subsampling stage where nearby nodes pool their information in a set of preselected sample nodes. A key component of the architecture is to remember the position of sampled nodes to permit computation of convolutional features at deeper layers. The second architecture, dubbed aggregation GNN, diffuses the signal through the graph and stores the sequence of diffused components observed by a designated node. This procedure effectively aggregates all components into a stream of information having temporal structure to which the convolution and pooling stages of regular CNNs can be applied. A multinode version of aggregation GNNs is further introduced for operation in large scale graphs. An important property of selection and aggregation GNNs is that they reduce to conventional CNNs when particularized to time signals reinterpreted as graph signals in a circulant graph. Comparative numerical analyses are performed in a source localization application over synthetic and real-world networks. Performance is also evaluated for an authorship attribution problem and text category classification. Multinode aggregation GNNs are consistently the best performing GNN architecture.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.00165](http://arxiv.org/abs/1805.00165)

##### PDF
[http://arxiv.org/pdf/1805.00165](http://arxiv.org/pdf/1805.00165)

