---
layout: post
title: "Generic CP-Supported CMSA for Binary Integer Linear Programs"
date: 2018-05-30 06:22:34
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Christian Blum, Haroldo Gambini Santos
mathjax: true
---

* content
{:toc}

##### Abstract
Construct, Merge, Solve and Adapt (CMSA) is a general hybrid metaheuristic for solving combinatorial optimization problems. At each iteration, CMSA (1) constructs feasible solutions to the tackled problem instance in a probabilistic way and (2) solves a reduced problem instance (if possible) to optimality. The construction of feasible solutions is hereby problem-specific, usually involving a fast greedy heuristic. The goal of this paper is to design a problem-agnostic CMSA variant whose exclusive input is an integer linear program (ILP). In order to reduce the complexity of this task, the current study is restricted to binary ILPs. In addition to a basic problem-agnostic CMSA variant, we also present an extended version that makes use of a constraint propagation engine for constructing solutions. The results show that our technique is able to match the upper bounds of the standalone application of CPLEX in the context of rather easy-to-solve instances, while it generally outperforms the standalone application of CPLEX in the context of hard instances. Moreover, the results indicate that the support of the constraint propagation engine is useful in the context of problems for which finding feasible solutions is rather difficult.

##### Abstract (translated by Google)
构建，合并，求解和适应（CMSA）是解决组合优化问题的通用混合型启发式算法。在每次迭代中，CMSA（1）以概率的方式构建解决问题实例的可行解，并（2）将减少的问题实例（如果可能的话）解决为最优。可行解决方案的构建特此针对具体问题，通常涉及快速贪婪的启发式。本文的目标是设计一个独立输入为整数线性程序（ILP）的问题不可知的CMSA变体。为了减少这项任务的复杂性，目前的研究仅限于二进制ILP。除了基本的与问题无关的CMSA变体之外，我们还提供了一个扩展版本，它使用约束传播引擎来构造解决方案。结果显示，我们的技术能够在相当容易解决的实例环境中匹配CPLEX独立应用程序的上限，而它通常优于CPLEX在硬实例上下文中的独立应用程序。此外，结果表明，约束传播引擎的支持在寻找可行解决方案相当困难的问题的背景下是有用的。

##### URL
[https://arxiv.org/abs/1805.11820](https://arxiv.org/abs/1805.11820)

##### PDF
[https://arxiv.org/pdf/1805.11820](https://arxiv.org/pdf/1805.11820)

