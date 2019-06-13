---
layout: post
title: "Neural Variational Inference For Estimating Uncertainty in Knowledge Graph Embeddings"
date: 2019-06-12 07:52:02
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding Inference Prediction Relation
author: Alexander I. Cowen-Rivers, Pasquale Minervini, Tim Rocktaschel, Matko Bovsnjak, Sebastian Riedel, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in Neural Variational Inference allowed for a renaissance in latent variable models in a variety of domains involving high-dimensional data. While traditional variational methods derive an analytical approximation for the intractable distribution over the latent variables, here we construct an inference network conditioned on the symbolic representation of entities and relation types in the Knowledge Graph, to provide the variational distributions. The new framework results in a highly-scalable method. Under a Bernoulli sampling framework, we provide an alternative justification for commonly used techniques in large-scale stochastic variational inference, which drastically reduce training time at a cost of an additional approximation to the variational lower bound. We introduce two models from this highly scalable probabilistic framework, namely the Latent Information and Latent Fact models, for reasoning over knowledge graph-based representations. Our Latent Information and Latent Fact models improve upon baseline performance under certain conditions. We use the learnt embedding variance to estimate predictive uncertainty during link prediction, and discuss the quality of these learnt uncertainty estimates. Our source code and datasets are publicly available online at https://github.com/alexanderimanicowenrivers/Neural-Variational-Knowledge-Graphs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04985](http://arxiv.org/abs/1906.04985)

##### PDF
[http://arxiv.org/pdf/1906.04985](http://arxiv.org/pdf/1906.04985)

