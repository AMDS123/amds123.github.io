---
layout: post
title: "Graph Neural Based End-to-end Data Association Framework for Online Multiple-Object Tracking"
date: 2019-07-11 15:43:38
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Optimization Detection
author: Xiaolong Jiang, Peizhao Li, Yanjing Li, Xiantong Zhen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present an end-to-end framework to settle data association in online Multiple-Object Tracking (MOT). Given detection responses, we formulate the frame-by-frame data association as Maximum Weighted Bipartite Matching problem, whose solution is learned using a neural network. The network incorporates an affinity learning module, wherein both appearance and motion cues are investigated to encode object feature representation and compute pairwise affinities. Employing the computed affinities as edge weights, the following matching problem on a bipartite graph is resolved by the optimization module, which leverages a graph neural network to adapt with the varying cardinalities of the association problem and solve the combinatorial hardness with favorable scalability and compatibility. To facilitate effective training of the proposed tracking network, we design a multi-level matrix loss in conjunction with the assembled supervision methodology. Being trained end-to-end, all modules in the tracker can co-adapt and co-operate collaboratively, resulting in improved model adaptiveness and less parameter-tuning efforts. Experiment results on the MOT benchmarks demonstrate the efficacy of the proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05315](http://arxiv.org/abs/1907.05315)

##### PDF
[http://arxiv.org/pdf/1907.05315](http://arxiv.org/pdf/1907.05315)

