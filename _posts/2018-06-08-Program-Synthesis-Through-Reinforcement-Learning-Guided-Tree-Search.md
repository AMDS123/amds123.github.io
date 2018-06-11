---
layout: post
title: "Program Synthesis Through Reinforcement Learning Guided Tree Search"
date: 2018-06-08 00:53:43
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Riley Simmons-Edler, Anders Miltner, Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
Program Synthesis is the task of generating a program from a provided specification. Traditionally, this has been treated as a search problem by the programming languages (PL) community and more recently as a supervised learning problem by the machine learning community. Here, we propose a third approach, representing the task of synthesizing a given program as a Markov decision process solvable via reinforcement learning(RL). From observations about the states of partial programs, we attempt to find a program that is optimal over a provided reward metric on pairs of programs and states. We instantiate this approach on a subset of the RISC-V assembly language operating on floating point numbers, and as an optimization inspired by search-based techniques from the PL community, we combine RL with a priority search tree. We evaluate this instantiation and demonstrate the effectiveness of our combined method compared to a variety of baselines, including a pure RL ablation and a state of the art Markov chain Monte Carlo search method on this task.

##### Abstract (translated by Google)
程序综合是根据提供的规范生成程序的任务。传统上，这被编程语言（PL）社区视为搜索问题，最近被机器学习社区视为监督学习问题。在这里，我们提出第三种方法，代表通过强化学习（RL）将综合给定程序作为马尔可夫决策过程可解的任务。从关于部分节目状态的观察中，我们试图找到一个节目，该节目在一对节目和状态中提供的奖励度量上是最优的。我们在运行在浮点数上的RISC-V汇编语言的一个子集上实例化了这种方法，并且作为来自PL社区的基于搜索的技术启发的优化，我们将RL与优先搜索树结合起来。我们评估了这个实例，并且证明了我们的组合方法与各种基线相比的有效性，包括纯RL消融和该任务中最先进的马尔可夫链蒙特卡罗搜索方法。

##### URL
[http://arxiv.org/abs/1806.02932](http://arxiv.org/abs/1806.02932)

##### PDF
[http://arxiv.org/pdf/1806.02932](http://arxiv.org/pdf/1806.02932)

