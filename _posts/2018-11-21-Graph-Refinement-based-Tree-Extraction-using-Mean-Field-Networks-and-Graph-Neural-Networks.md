---
layout: post
title: "Graph Refinement based Tree Extraction using Mean-Field Networks and Graph Neural Networks"
date: 2018-11-21 10:50:31
categories: arXiv_CV
tags: arXiv_CV Embedding Inference Gradient_Descent
author: Raghavendra Selvan, Thomas Kipf, Max Welling, Jesper H Pedersen, Jens Petersen, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Graph refinement, or the task of obtaining subgraphs of interest from over-complete graphs, can have many varied applications. In this work, we extract tree structures from image data by, first deriving a graph-based representation of the volumetric data and then, posing tree extraction as a graph refinement task. We present two methods to perform graph refinement. First, we use mean-field approximation (MFA) to approximate the posterior density over the subgraphs from which the optimal subgraph of interest can be estimated. Mean field networks (MFNs) are used for inference based on the interpretation that iterations of MFA can be seen as feed-forward operations in a neural network. This allows us to learn the model parameters using gradient descent. Second, we present a supervised learning approach using graph neural networks (GNNs) which can be seen as generalisations of MFNs. Subgraphs are obtained by jointly training a GNN based encoder-decoder pair, wherein the encoder learns useful edge embeddings from which the edge probabilities are predicted using a simple decoder. We discuss connections between the two classes of methods and compare them for the task of extracting airways from 3D, low-dose, chest CT data. We show that both the MFN and GNN models show significant improvement when compared to a baseline method, that is similar to a top performing method in the EXACT'09 Challenge, in detecting more branches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08674](http://arxiv.org/abs/1811.08674)

##### PDF
[http://arxiv.org/pdf/1811.08674](http://arxiv.org/pdf/1811.08674)

