---
layout: post
title: "Provably Efficient Q-Learning with Low Switching Cost"
date: 2019-05-30 04:35:13
categories: arXiv_AI
tags: arXiv_AI
author: Yu Bai, Tengyang Xie, Nan Jiang, Yu-Xiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We take initial steps in studying PAC-MDP algorithms with limited adaptivity, that is, algorithms that change its exploration policy as infrequently as possible during regret minimization. This is motivated by the difficulty of running fully adaptive algorithms in real-world applications (such as medical domains), and we propose to quantify adaptivity using the notion of local switching cost. Our main contribution, Q-Learning with UCB2 exploration, is a model-free algorithm for H-step episodic MDP that achieves sublinear regret whose local switching cost in K episodes is $O(H^3SA\log K)$, and we provide a lower bound of $\Omega(HSA)$ on the local switching cost for any no-regret algorithm. Our algorithm can be naturally adapted to the concurrent setting, which yields nontrivial results that improve upon prior work in certain aspects.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12849](http://arxiv.org/abs/1905.12849)

##### PDF
[http://arxiv.org/pdf/1905.12849](http://arxiv.org/pdf/1905.12849)

