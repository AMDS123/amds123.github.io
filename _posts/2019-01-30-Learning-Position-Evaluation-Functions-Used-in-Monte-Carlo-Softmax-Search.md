---
layout: post
title: "Learning Position Evaluation Functions Used in Monte Carlo Softmax Search"
date: 2019-01-30 08:21:34
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Harukazu Igarashi, Yuichi Morioka, Kazumasa Yamamoto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper makes two proposals for Monte Carlo Softmax Search, which is a recently proposed method that is classified as a selective search like the Monte Carlo Tree Search. The first proposal separately defines the node-selection and backup policies to allow researchers to freely design a node-selection policy based on their searching strategies and confirms the principal variation produced by the Monte Carlo Softmax Search to that produced by a minimax search. The second proposal modifies commonly used learning methods for positional evaluation functions. In our new proposals, evaluation functions are learned by Monte Carlo sampling, which is performed with the backup policy in the search tree produced by Monte Carlo Softmax Search. The learning methods under consideration include supervised learning, reinforcement learning, regression learning, and search bootstrapping. Our sampling-based learning not only uses current positions and principal variations but also the internal nodes and important variations of a search tree. This step reduces the number of games necessary for learning. New learning rules are derived for sampling-based learning based on the Monte Carlo Softmax Search and combinations of the modified learning methods are also proposed in this paper.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10706](http://arxiv.org/abs/1901.10706)

##### PDF
[http://arxiv.org/pdf/1901.10706](http://arxiv.org/pdf/1901.10706)

