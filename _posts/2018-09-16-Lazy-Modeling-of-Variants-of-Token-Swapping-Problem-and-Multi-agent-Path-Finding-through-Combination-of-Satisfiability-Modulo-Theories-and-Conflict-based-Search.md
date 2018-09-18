---
layout: post
title: "Lazy Modeling of Variants of Token Swapping Problem and Multi-agent Path Finding through Combination of Satisfiability Modulo Theories and Conflict-based Search"
date: 2018-09-16 21:19:35
categories: arXiv_AI
tags: arXiv_AI
author: Pavel Surynek
mathjax: true
---

* content
{:toc}

##### Abstract
We address item relocation problems in graphs in this paper. We assume items placed in vertices of an undirected graph with at most one item per vertex. Items can be moved across edges while various constraints depending on the type of relocation problem must be satisfied. We introduce a general problem formulation that encompasses known types of item relocation problems such as multi-agent path finding (MAPF) and token swapping (TSWAP). In this formulation we express two new types of relocation problems derived from token swapping that we call token rotation (TROT) and token permutation (TPERM). Our solving approach for item relocation combines satisfiability modulo theory (SMT) with conflict-based search (CBS). We interpret CBS in the SMT framework where we start with the basic model and refine the model with a collision resolution constraint whenever a collision between items occurs in the current solution. The key difference between the standard CBS and our SMT-based modification of CBS (SMT-CBS) is that the standard CBS branches the search to resolve the collision while in SMT-CBS we iteratively add a single disjunctive collision resolution constraint. Experimental evaluation on several benchmarks shows that the SMT-CBS algorithm significantly outperforms the standard CBS. We also compared SMT-CBS with a modification of the SAT-based MDD-SAT solver that uses an eager modeling of item relocation in which all potential collisions are eliminated by constrains in advance. Experiments show that lazy approach in SMT-CBS produce fewer constraint than MDD-SAT and also achieves faster solving run-times.

##### Abstract (translated by Google)
我们在本文的图表中解决项目重定位问题。我们假设项目放置在无向图的顶点中，每个顶点最多一个项目。项目可以跨边移动，同时必须满足取决于重定位问题类型的各种约束。我们引入了一个通用问题公式，其中包含已知类型的项目重定位问题，例如多代理路径查找（MAPF）和令牌交换（TSWAP）。在这个公式中，我们表达了两种新的重定位问题类型，它们来自令牌交换，我们称之为令牌轮换（TROT）和令牌置换（TPERM）。我们的项目重定位解决方法将可满足模理论（SMT）与基于冲突的搜索（CBS）相结合。我们在SMT框架中解释CBS，我们从基本模型开始，并在当前解决方案中发生项目之间的冲突时使用冲突解决约束来细化模型。标准CBS和我们基于SMT的CBS（SMT-CBS）修改之间的关键区别在于标准CBS分支搜索以解决冲突，而在SMT-CBS中我们迭代地添加单个析取冲突解决约束。几个基准测试的实验评估表明，SMT-CBS算法明显优于标准CBS。我们还将SMT-CBS与基于SAT的MDD-SAT求解器的修改进行了比较，该解算器使用项目重定位的急切建模，其中所有潜在的碰撞都通过预先约束来消除。实验表明，SMT-CBS中的惰性方法比MDD-SAT产生更少的约束，并且还实现了更快的求解运行时间。

##### URL
[http://arxiv.org/abs/1809.05959](http://arxiv.org/abs/1809.05959)

##### PDF
[http://arxiv.org/pdf/1809.05959](http://arxiv.org/pdf/1809.05959)

