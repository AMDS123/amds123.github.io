---
layout: post
title: "Practical Algorithms for Multi-Stage Voting Rules with Parallel Universes Tiebreaking"
date: 2019-01-16 21:41:39
categories: arXiv_AI
tags: arXiv_AI
author: Jun Wang, Sujoy Sikdar, Tyler Shepherd, Zhibing Zhao, Chunheng Jiang, Lirong Xia
mathjax: true
---

* content
{:toc}

##### Abstract
STV and ranked pairs (RP) are two well-studied voting rules for group decision-making. They proceed in multiple rounds, and are affected by how ties are broken in each round. However, the literature is surprisingly vague about how ties should be broken. We propose the first algorithms for computing the set of alternatives that are winners under some tiebreaking mechanism under STV and RP, which is also known as parallel-universes tiebreaking (PUT). Unfortunately, PUT-winners are NP-complete to compute under STV and RP, and standard search algorithms from AI do not apply. We propose multiple DFS-based algorithms along with pruning strategies, heuristics, sampling and machine learning to prioritize search direction to significantly improve the performance. We also propose novel ILP formulations for PUT-winners under STV and RP, respectively. Experiments on synthetic and real-world data show that our algorithms are overall faster than ILP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09791](http://arxiv.org/abs/1901.09791)

##### PDF
[http://arxiv.org/pdf/1901.09791](http://arxiv.org/pdf/1901.09791)

