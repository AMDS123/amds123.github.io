---
layout: post
title: "Online algorithms for POMDPs with continuous state, action, and observation spaces"
date: 2018-09-06 00:46:54
categories: arXiv_AI
tags: arXiv_AI
author: Zachary Sunberg, Mykel Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
Online solvers for partially observable Markov decision processes have been applied to problems with large discrete state spaces, but continuous state, action, and observation spaces remain a challenge. This paper begins by investigating double progressive widening (DPW) as a solution to this challenge. However, we prove that this modification alone is not sufficient because the belief representations in the search tree collapse to a single particle causing the algorithm to converge to a policy that is suboptimal regardless of the computation time. This paper proposes and evaluates two new algorithms, POMCPOW and PFT-DPW, that overcome this deficiency by using weighted particle filtering. Simulation results show that these modifications allow the algorithms to be successful where previous approaches fail.

##### Abstract (translated by Google)
部分可观察马尔可夫决策过程的在线求解器已应用于具有大离散状态空间的问题，但连续状态，动作和观察空间仍然是一个挑战。本文首先研究双渐进加宽（DPW）作为这一挑战的解决方案。然而，我们证明单独的这种修改是不充分的，因为搜索树中的置信表示会崩溃成单个粒子，导致算法收敛到不管计算时间而不是最优的策略。本文提出并评估了两种新算法POMCPOW和PFT-DPW，它们通过加权粒子滤波克服了这一缺陷。仿真结果表明，这些修改允许算法在以前的方法失败时成功。

##### URL
[http://arxiv.org/abs/1709.06196](http://arxiv.org/abs/1709.06196)

##### PDF
[http://arxiv.org/pdf/1709.06196](http://arxiv.org/pdf/1709.06196)

