---
layout: post
title: "Multitask Learning on Graph Neural Networks - Learning Multiple Graph Centrality Measures with a Unified Network"
date: 2018-11-08 17:56:26
categories: arXiv_AI
tags: arXiv_AI Embedding Deep_Learning Relation
author: Pedro H. C. Avelar, Henrique Lemos, Marcelo O. R. Prates, Luis Lamb
mathjax: true
---

* content
{:toc}

##### Abstract
The application of deep learning to symbolic domains remains an active research endeavour. Graph neural networks (GNN), consisting of trained neural modules which can be arranged in different topologies at run time, are sound alternatives to tackle relational problems which lend themselves to graph representations. In this paper, we show that GNNs are capable of multitask learning, which can be naturally enforced by training the model to refine a single set of multidimensional embeddings $\in \mathbb{R}^d$ and decode them into multiple outputs by connecting MLPs at the end of the pipeline. We demonstrate the multitask learning capability of the model in the relevant relational problem of estimating network centrality measures, i.e. is vertex $v_1$ more central than vertex $v_2$ given centrality $c$?. We then show that a GNN can be trained to develop a $lingua$ $franca$ of vertex embeddings from which all relevant information about any of the trained centrality measures can be decoded. The proposed model achieves $89\%$ accuracy on a test dataset of random instances with up to 128 vertices and is shown to generalise to larger problem sizes. The model is also shown to obtain reasonable accuracy on a dataset of real world instances with up to 4k vertices, vastly surpassing the sizes of the largest instances with which the model was trained ($n=128$). Finally, we believe that our contributions attest to the potential of GNNs in symbolic domains in general and in relational learning in particular.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.07695](http://arxiv.org/abs/1809.07695)

##### PDF
[http://arxiv.org/pdf/1809.07695](http://arxiv.org/pdf/1809.07695)

