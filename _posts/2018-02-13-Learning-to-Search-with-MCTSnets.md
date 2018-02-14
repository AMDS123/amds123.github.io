---
layout: post
title: "Learning to Search with MCTSnets"
date: 2018-02-13 16:10:10
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Arthur Guez, Th&#xe9;ophane Weber, Ioannis Antonoglou, Karen Simonyan, Oriol Vinyals, Daan Wierstra, R&#xe9;mi Munos, David Silver
mathjax: true
---

* content
{:toc}

##### Abstract
Planning problems are among the most important and well-studied problems in artificial intelligence. They are most typically solved by tree search algorithms that simulate ahead into the future, evaluate future states, and back-up those evaluations to the root of a search tree. Among these algorithms, Monte-Carlo tree search (MCTS) is one of the most general, powerful and widely used. A typical implementation of MCTS uses cleverly designed rules, optimized to the particular characteristics of the domain. These rules control where the simulation traverses, what to evaluate in the states that are reached, and how to back-up those evaluations. In this paper we instead learn where, what and how to search. Our architecture, which we call an MCTSnet, incorporates simulation-based search inside a neural network, by expanding, evaluating and backing-up a vector embedding. The parameters of the network are trained end-to-end using gradient-based optimisation. When applied to small searches in the well known planning problem Sokoban, the learned search algorithm significantly outperformed MCTS baselines.

##### Abstract (translated by Google)
规划问题是人工智能中最重要和研究得最深入的问题之一。它们通常是通过树搜索算法来解决的，这些算法可以模拟未来，评估未来状态，并将这些评估备份到搜索树的根。在这些算法中，蒙特卡洛树搜索（MCTS）是最普遍，最强大和最广泛使用的算法之一。 MCTS的典型实现使用巧妙设计的规则，针对域的特定特征进行了优化。这些规则控制模拟遍历的位置，在达到的状态下评估什么，以及如何备份这些评估。在本文中，我们反而了解了在哪里，如何搜索。我们称之为MCTSnet的架构通过扩展，评估和备份矢量嵌入，将基于仿真的搜索结合到神经网络中。网络参数采用基于梯度的优化进行端对端培训。当应用于众所周知的计划问题Sokoban的小搜索时，学习搜索算法明显优于MCTS基线。

##### URL
[http://arxiv.org/abs/1802.04697](http://arxiv.org/abs/1802.04697)

##### PDF
[http://arxiv.org/pdf/1802.04697](http://arxiv.org/pdf/1802.04697)

