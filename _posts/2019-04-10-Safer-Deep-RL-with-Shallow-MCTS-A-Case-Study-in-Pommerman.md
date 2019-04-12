---
layout: post
title: "Safer Deep RL with Shallow MCTS: A Case Study in Pommerman"
date: 2019-04-10 14:34:40
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Bilal Kartal, Pablo Hernandez-Leal, Chao Gao, Matthew E. Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
Safe reinforcement learning has many variants and it is still an open research problem. Here, we focus on how to use action guidance by means of a non-expert demonstrator to avoid catastrophic events in a domain with sparse, delayed, and deceptive rewards: the recently-proposed multi-agent benchmark of Pommerman. This domain is very challenging for reinforcement learning (RL) --- past work has shown that model-free RL algorithms fail to achieve significant learning. In this paper, we shed light into the reasons behind this failure by exemplifying and analyzing the high rate of catastrophic events (i.e., suicides) that happen under random exploration in this domain. While model-free random exploration is typically futile, we propose a new framework where even a non-expert simulated demonstrator, e.g., planning algorithms such as Monte Carlo tree search with small number of rollouts, can be integrated to asynchronous distributed deep reinforcement learning methods. Compared to vanilla deep RL algorithms, our proposed methods both learn faster and converge to better policies on a two-player mini version of the Pommerman game.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05759](http://arxiv.org/abs/1904.05759)

##### PDF
[http://arxiv.org/pdf/1904.05759](http://arxiv.org/pdf/1904.05759)

