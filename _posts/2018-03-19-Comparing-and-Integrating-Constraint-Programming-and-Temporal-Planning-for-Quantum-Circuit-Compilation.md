---
layout: post
title: "Comparing and Integrating Constraint Programming and Temporal Planning for Quantum Circuit Compilation"
date: 2018-03-19 01:29:02
categories: arXiv_AI
tags: arXiv_AI
author: Kyle E. C. Booth, Minh Do, J. Christopher Beck, Eleanor Rieffel, Davide Venturelli, Jeremy Frank
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the makespan-minimization problem of compiling a general class of quantum algorithms into near-term quantum processors has been introduced to the AI community. The research demonstrated that temporal planning is a strong approach for a class of quantum circuit compilation (QCC) problems. In this paper, we explore the use of constraint programming (CP) as an alternative and complementary approach to temporal planning. We extend previous work by introducing two new problem variations that incorporate important characteristics identified by the quantum computing community. We apply temporal planning and CP to the baseline and extended QCC problems as both stand-alone and hybrid approaches. Our hybrid methods use solutions found by temporal planning to warm start CP, leveraging the ability of the former to find satisficing solutions to problems with a high degree of task optionality, an area that CP typically struggles with. The CP model, benefiting from inferred bounds on planning horizon length and task counts provided by the warm start, is then used to find higher quality solutions. Our empirical evaluation indicates that while stand-alone CP is only competitive for the smallest problems, CP in our hybridization with temporal planning out-performs stand-alone temporal planning in the majority of problem classes.

##### Abstract (translated by Google)
最近，人工智能团体引入了将一般类别的量子算法编译成近期量子处理器的完整范围最小化问题。研究表明时间规划是一类量子电路编译（QCC）问题的强有力的方法。在本文中，我们探讨了使用约束规划（CP）作为时间规划的替代和补充方法。我们通过引入两个新的问题变体来扩展以前的工作，这些变体包含量子计算社区确定的重要特征我们将时间计划和CP应用于基线和扩展的QCC问题，既可以作为独立的方法，也可以作为混合方法应用。我们的混合方法使用时间计划中找到的解决方案来加热启动CP，利用前者的能力来找到满意解决方案，以解决具有高度任务选择性的问题，这是CP通常需要解决的问题。 CP模型受益于热启动提供的计划范围长度和任务计数的推断范围，然后用于找到更高质量的解决方案。我们的实证评估表明，虽然独立CP只对最小的问题具有竞争力，但我们与时间规划的杂交中的CP在大多数问题类别中超出了独立的时间规划。

##### URL
[https://arxiv.org/abs/1803.06775](https://arxiv.org/abs/1803.06775)

##### PDF
[https://arxiv.org/pdf/1803.06775](https://arxiv.org/pdf/1803.06775)

