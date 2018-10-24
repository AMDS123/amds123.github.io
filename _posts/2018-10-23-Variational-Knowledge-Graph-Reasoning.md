---
layout: post
title: "Variational Knowledge Graph Reasoning"
date: 2018-10-23 04:51:29
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Attention Inference Prediction Relation
author: Wenhu Chen, Wenhan Xiong, Xifeng Yan, William Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Inferring missing links in knowledge graphs (KG) has attracted a lot of attention from the research community. In this paper, we tackle a practical query answering task involving predicting the relation of a given entity pair. We frame this prediction problem as an inference problem in a probabilistic graphical model and aim at resolving it from a variational inference perspective. In order to model the relation between the query entity pair, we assume that there exists an underlying latent variable (paths connecting two nodes) in the KG, which carries the equivalent semantics of their relations. However, due to the intractability of connections in large KGs, we propose to use variation inference to maximize the evidence lower bound. More specifically, our framework (\textsc{Diva}) is composed of three modules, i.e. a posterior approximator, a prior (path finder), and a likelihood (path reasoner). By using variational inference, we are able to incorporate them closely into a unified architecture and jointly optimize them to perform KG reasoning. With active interactions among these sub-modules, \textsc{Diva} is better at handling noise and coping with more complex reasoning scenarios. In order to evaluate our method, we conduct the experiment of the link prediction task on multiple datasets and achieve state-of-the-art performances on both datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.06581](http://arxiv.org/abs/1803.06581)

##### PDF
[http://arxiv.org/pdf/1803.06581](http://arxiv.org/pdf/1803.06581)

