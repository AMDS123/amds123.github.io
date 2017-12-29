---
layout: post
title: "POMCPOW: An online algorithm for POMDPs with continuous state, action, and observation spaces"
date: 2017-12-27 01:28:32
categories: arXiv_AI
tags: arXiv_AI
author: Zachary Sunberg, Mykel Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
Online solvers for partially observable Markov decision processes have been applied to problems with large discrete state spaces, but continuous state, action, and observation spaces remain a challenge. This paper begins by investigating double progressive widening (DPW) as a solution to this challenge. However, we prove that this modification alone is not sufficient because the belief representations in the search tree collapse to a single particle causing the algorithm to converge to a policy that is suboptimal regardless of the computation time. The main contribution of the paper is to propose a new algorithm, POMCPOW, that incorporates DPW and weighted particle filtering to overcome this deficiency and attack continuous problems. Simulation results show that these modifications allow the algorithm to be successful where previous approaches fail.

##### Abstract (translated by Google)
部分可观察的马尔科夫决策过程的在线求解器已经应用于大离散状态空间的问题，但连续的状态，行动和观察空间仍然是一个挑战。本文首先研究双进展拓展（DPW）作为解决这一挑战的方法。然而，我们证明这种修改本身是不够的，因为搜索树中的信念表示折叠成单个粒子，导致算法收敛到不理会计算时间的次优策略。本文的主要贡献在于提出了一种新的算法POMCPOW，该算法结合了DPW和加权粒子滤波来克服这个缺陷并攻击连续问题。仿真结果表明，这些修改允许算法在以前的方法失败的地方成功。

##### URL
[http://arxiv.org/abs/1709.06196](http://arxiv.org/abs/1709.06196)

##### PDF
[http://arxiv.org/pdf/1709.06196](http://arxiv.org/pdf/1709.06196)

