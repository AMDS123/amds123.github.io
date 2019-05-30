---
layout: post
title: "Graph DNA: Deep Neighborhood Aware Graph Encoding for Collaborative Filtering"
date: 2019-05-29 04:57:02
categories: arXiv_AI
tags: arXiv_AI Regularization Recommendation
author: Liwei Wu, Hsiang-Fu Yu, Nikhil Rao, James Sharpnack, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider recommender systems with side information in the form of graphs. Existing collaborative filtering algorithms mainly utilize only immediate neighborhood information and have a hard time taking advantage of deeper neighborhoods beyond 1-2 hops. The main caveat of exploiting deeper graph information is the rapidly growing time and space complexity when incorporating information from these neighborhoods. In this paper, we propose using Graph DNA, a novel Deep Neighborhood Aware graph encoding algorithm, for exploiting deeper neighborhood information. DNA encoding computes approximate deep neighborhood information in linear time using Bloom filters, a space-efficient probabilistic data structure and results in a per-node encoding that is logarithmic in the number of nodes in the graph. It can be used in conjunction with both feature-based and graph-regularization-based collaborative filtering algorithms. Graph DNA has the advantages of being memory and time efficient and providing additional regularization when compared to directly using higher order graph information. We conduct experiments on real-world datasets, showing graph DNA can be easily used with 4 popular collaborative filtering algorithms and consistently leads to a performance boost with little computational and memory overhead.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12217](http://arxiv.org/abs/1905.12217)

##### PDF
[http://arxiv.org/pdf/1905.12217](http://arxiv.org/pdf/1905.12217)

