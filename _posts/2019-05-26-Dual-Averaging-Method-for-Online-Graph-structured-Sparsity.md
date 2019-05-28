---
layout: post
title: "Dual Averaging Method for Online Graph-structured Sparsity"
date: 2019-05-26 02:42:16
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization Classification
author: Baojian Zhou, Feng Chen, Yiming Ying
mathjax: true
---

* content
{:toc}

##### Abstract
Online learning algorithms update models via one sample per iteration, thus efficient to process large-scale datasets and useful to detect malicious events for social benefits, such as disease outbreak and traffic congestion on the fly. However, existing algorithms for graph-structured models focused on the offline setting and the least square loss, incapable for online setting, while methods designed for online setting cannot be directly applied to the problem of complex (usually non-convex) graph-structured sparsity model. To address these limitations, in this paper we propose a new algorithm for graph-structured sparsity constraint problems under online setting, which we call \textsc{GraphDA}. The key part in \textsc{GraphDA} is to project both averaging gradient (in dual space) and primal variables (in primal space) onto lower dimensional subspaces, thus capturing the graph-structured sparsity effectively. Furthermore, the objective functions assumed here are generally convex so as to handle different losses for online learning settings. To the best of our knowledge, \textsc{GraphDA} is the first online learning algorithm for graph-structure constrained optimization problems. To validate our method, we conduct extensive experiments on both benchmark graph and real-world graph datasets. Our experiment results show that, compared to other baseline methods, \textsc{GraphDA} not only improves classification performance, but also successfully captures graph-structured features more effectively, hence stronger interpretability.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10714](http://arxiv.org/abs/1905.10714)

##### PDF
[http://arxiv.org/pdf/1905.10714](http://arxiv.org/pdf/1905.10714)

