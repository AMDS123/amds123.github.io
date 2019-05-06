---
layout: post
title: "D-VAE: A Variational Autoencoder for Directed Acyclic Graphs"
date: 2019-04-24 22:22:57
categories: arXiv_CV
tags: arXiv_CV NAS Optimization
author: Muhan Zhang, Shali Jiang, Zhicheng Cui, Roman Garnett, Yixin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Graph structured data are abundant in the real world. Among different graph types, directed acyclic graphs (DAGs) are of particular interests to machine learning researchers, as many machine learning models are realized as computations on DAGs, including neural networks and Bayesian networks. In this paper, we study deep generative models for DAGs, and propose a novel DAG variational autoencoder (D-VAE). To encode DAGs into the latent space, we leverage graph neural networks. We propose a DAG-style asynchronous message passing scheme that allows encoding the computations defined by DAGs, rather than using existing simultaneous message passing schemes to encode the graph structures. We demonstrate the effectiveness of our proposed D-VAE through two tasks: neural architecture search and Bayesian network structure learning. Experiments show that our model not only generates novel and valid DAGs, but also produces a smooth latent space that facilitates searching for DAGs with better performance through Bayesian optimization.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.11088](https://arxiv.org/abs/1904.11088)

##### PDF
[https://arxiv.org/pdf/1904.11088](https://arxiv.org/pdf/1904.11088)

