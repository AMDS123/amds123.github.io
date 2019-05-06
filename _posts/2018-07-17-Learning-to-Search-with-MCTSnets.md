---
layout: post
title: "Learning to Search with MCTSnets"
date: 2018-07-17 14:16:12
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Arthur Guez, Théophane Weber, Ioannis Antonoglou, Karen Simonyan, Oriol Vinyals, Daan Wierstra, Rémi Munos, David Silver
mathjax: true
---

* content
{:toc}

##### Abstract
Planning problems are among the most important and well-studied problems in artificial intelligence. They are most typically solved by tree search algorithms that simulate ahead into the future, evaluate future states, and back-up those evaluations to the root of a search tree. Among these algorithms, Monte-Carlo tree search (MCTS) is one of the most general, powerful and widely used. A typical implementation of MCTS uses cleverly designed rules, optimized to the particular characteristics of the domain. These rules control where the simulation traverses, what to evaluate in the states that are reached, and how to back-up those evaluations. In this paper we instead learn where, what and how to search. Our architecture, which we call an MCTSnet, incorporates simulation-based search inside a neural network, by expanding, evaluating and backing-up a vector embedding. The parameters of the network are trained end-to-end using gradient-based optimisation. When applied to small searches in the well known planning problem Sokoban, the learned search algorithm significantly outperformed MCTS baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.04697](https://arxiv.org/abs/1802.04697)

##### PDF
[https://arxiv.org/pdf/1802.04697](https://arxiv.org/pdf/1802.04697)

