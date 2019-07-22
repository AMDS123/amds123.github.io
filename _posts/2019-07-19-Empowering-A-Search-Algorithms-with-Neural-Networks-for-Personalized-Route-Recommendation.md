---
layout: post
title: "Empowering A* Search Algorithms with Neural Networks for Personalized Route Recommendation"
date: 2019-07-19 12:47:00
categories: arXiv_AI
tags: arXiv_AI Attention RNN Recommendation
author: Jingyuan Wang, Ning Wu, Wayne Xin Zhao, Fanzhang Peng, Xin Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Personalized Route Recommendation (PRR) aims to generate user-specific route suggestions in response to users' route queries. Early studies cast the PRR task as a pathfinding problem on graphs, and adopt adapted search algorithms by integrating heuristic strategies. Although these methods are effective to some extent, they require setting the cost functions with heuristics. In addition, it is difficult to utilize useful context information in the search procedure. To address these issues, we propose using neural networks to automatically learn the cost functions of a classic heuristic algorithm, namely A* algorithm, for the PRR task. Our model consists of two components. First, we employ attention-based Recurrent Neural Networks (RNN) to model the cost from the source to the candidate location by incorporating useful context information. Instead of learning a single cost value, the RNN component is able to learn a time-varying vectorized representation for the moving state of a user. Second, we propose to use a value network for estimating the cost from a candidate location to the destination. For capturing structural characteristics, the value network is built on top of improved graph attention networks by incorporating the moving state of a user and other context information. The two components are integrated in a principled way for deriving a more accurate cost of a candidate location. Extensive experiment results on three real-world datasets have shown the effectiveness and robustness of the proposed model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08489](http://arxiv.org/abs/1907.08489)

##### PDF
[http://arxiv.org/pdf/1907.08489](http://arxiv.org/pdf/1907.08489)

