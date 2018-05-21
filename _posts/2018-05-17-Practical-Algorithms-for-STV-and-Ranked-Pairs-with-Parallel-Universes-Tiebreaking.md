---
layout: post
title: "Practical Algorithms for STV and Ranked Pairs with Parallel Universes Tiebreaking"
date: 2018-05-17 23:20:57
categories: arXiv_AI
tags: arXiv_AI
author: Jun Wang, Sujoy Sikdar, Tyler Shepherd, Zhibing Zhao, Chunheng Jiang, Lirong Xia
mathjax: true
---

* content
{:toc}

##### Abstract
STV and ranked pairs (RP) are two well-studied voting rules for group decision-making. They proceed in multiple rounds, and are affected by how ties are broken in each round. However, the literature is surprisingly vague about how ties should be broken. We propose the first algorithms for computing the set of alternatives that are winners under some tiebreaking mechanism under STV and RP, which is also known as parallel-universes tiebreaking (PUT). Unfortunately, PUT-winners are NP-complete to compute under STV and RP, and standard search algorithms from AI do not apply. We propose multiple DFS-based algorithms along with pruning strategies and heuristics to prioritize search direction to significantly improve the performance using machine learning. We also propose novel ILP formulations for PUT-winners under STV and RP, respectively. Experiments on synthetic and real-world data show that our algorithms are overall significantly faster than ILP, while there are a few cases where ILP is significantly faster for RP.

##### Abstract (translated by Google)
STV和排名对（RP）是两组研究投票规则的集体决策。他们分多轮进行，受到每轮中关系如何破裂的影响。然而，关于如何打破关系的文献令人惊讶地模糊。我们提出了第一种算法，用于计算在STV和RP下的某些tiebreaking机制下获胜者的替代方案，也称为并行宇宙tiebreaking（PUT）。不幸的是，PUT获胜者在STV和RP下是NP完全计算的，并且来自AI的标准搜索算法不适用。我们提出了多种基于DFS的算法，以及修剪策略和启发式优先搜索方向，以显着提高机器学习的性能。我们还分别针对STV和RP下的PUT获胜者提出了新颖的ILP配方。综合和实际数据的实验表明，我们的算法总体上比ILP快得多，而在少数情况下，ILP对于RP来说要快得多。

##### URL
[http://arxiv.org/abs/1805.06992](http://arxiv.org/abs/1805.06992)

##### PDF
[http://arxiv.org/pdf/1805.06992](http://arxiv.org/pdf/1805.06992)

