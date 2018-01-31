---
layout: post
title: "Bounded Policy Synthesis for POMDPs with Safe-Reachability Objectives"
date: 2018-01-29 22:06:40
categories: arXiv_AI
tags: arXiv_AI
author: Yue Wang, Swarat Chaudhuri, Lydia E. Kavraki
mathjax: true
---

* content
{:toc}

##### Abstract
Planning robust executions under uncertainty is a fundamental challenge for building autonomous robots. Partially Observable Markov Decision Processes (POMDPs) provide a standard framework for modeling uncertainty in many robot applications. A key algorithmic problem for POMDPs is policy synthesis. While this problem has traditionally been posed w.r.t. optimality objectives, many robot applications are better modeled by POMDPs where the objective is a boolean requirement. In this paper, we study the latter problem in a setting where the requirement is a safe-reachability property, which states that with a probability above a certain threshold, it is possible to eventually reach a goal state while satisfying a safety requirement. The central challenge in our problem is that it requires reasoning over a vast space of probability distributions. What's more, it has been shown that policy synthesis of POMDPs with reachability objectives is undecidable in general. To address these challenges, we introduce the notion of a goal-constrained belief space, which only contains beliefs (probability distributions over states) reachable from the initial belief under desired executions. This constrained space is generally much smaller than the original belief space. Our approach compactly represents this space over a bounded horizon using symbolic constraints, and employs an incremental Satisfiability Modulo Theories (SMT) solver to efficiently search for a valid policy over it. We evaluate our method using a case study involving a partially observable robotics domain with uncertain obstacles. Our results suggest that it is possible to synthesize policies over large belief spaces with a small number of SMT solver calls by focusing on goal-constrained belief space, and our method o ers a stronger guarantee of both safety and reachability than alternative unconstrained/constrained POMDP formulations.

##### Abstract (translated by Google)
规划不确定性下的强大执行是构建自主机器人的一个基本挑战。部分可观测马尔可夫决策过程（POMDP）为许多机器人应用中的不确定性建模提供了一个标准框架。 POMDP的关键算法问题是政策综合。这个问题在传统上是由w.r.t.最优目标，许多机器人应用程序更好地模拟POMDPs的目标是一个布尔的要求。在本文中，我们研究后一个问题，在需求是一个安全可达性的环境中，这个环境表示在一定的阈值以上的概率，有可能最终达到目标状态，同时满足安全要求。我们问题的核心挑战在于它需要对概率分布的广阔空间进行推理。而且，已经表明，具有可达性目标的POMDP的政策综合是不可判定的。为了应对这些挑战，我们引入了一个目标约束信念空间的概念，它只包含在期望的执行过程中从初始信念可达到的信念（状态概率分布）。这个受约束的空间通常远小于原始的信念空间。我们的方法使用符号约束紧凑地表示有界平面上的这个空间，并采用增量可满足模理论（SMT）解算器来高效地搜索有效的策略。我们评估我们的方法使用案例研究涉及部分可观察的机器人领域与不确定的障碍。我们的研究结果表明，有可能通过聚焦于目标受限的信念空间，用少量的SMT求解器调用来综合大信念空间上的策略，而且我们的方法比替代的无约束/受约束的POMDP更能保证安全性和可达性配方。

##### URL
[http://arxiv.org/abs/1801.09780](http://arxiv.org/abs/1801.09780)

##### PDF
[http://arxiv.org/pdf/1801.09780](http://arxiv.org/pdf/1801.09780)

