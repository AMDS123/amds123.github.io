---
layout: post
title: "Vulcan: A Monte Carlo Algorithm for Large Chance Constrained MDPs with Risk Bounding Functions"
date: 2018-09-04 19:42:22
categories: arXiv_AI
tags: arXiv_AI Relation
author: Benjamin J Ayton, Brian C Williams
mathjax: true
---

* content
{:toc}

##### Abstract
Chance Constrained Markov Decision Processes maximize reward subject to a bounded probability of failure, and have been frequently applied for planning with potentially dangerous outcomes or unknown environments. Solution algorithms have required strong heuristics or have been limited to relatively small problems with up to millions of states, because the optimal action to take from a given state depends on the probability of failure in the rest of the policy, leading to a coupled problem that is difficult to solve. In this paper we examine a generalization of a CCMDP that trades off probability of failure against reward through a functional relationship. We derive a constraint that can be applied to each state history in a policy individually, and which guarantees that the chance constraint will be satisfied. The approach decouples states in the CCMDP, so that large problems can be solved efficiently. We then introduce Vulcan, which uses our constraint in order to apply Monte Carlo Tree Search to CCMDPs. Vulcan can be applied to problems where it is unfeasible to generate the entire state space, and policies must be returned in an anytime manner. We show that Vulcan and its variants run tens to hundreds of times faster than linear programming methods, and over ten times faster than heuristic based methods, all without the need for a heuristic, and returning solutions with a mean suboptimality on the order of a few percent. Finally, we use Vulcan to solve for a chance constrained policy in a CCMDP with over $10^{13}$ states in 3 minutes.

##### Abstract (translated by Google)
机会约束马尔可夫决策过程使受到有限的失败概率的奖励最大化，并且经常被应用于具有潜在危险结果或未知环境的规划。解决方案算法需要强大的启发式算法，或者仅限于数百万个州的相对较小的问题，因为从给定状态获取的最佳操作取决于策略其余部分中的失败概率，从而导致耦合问题很难解决。在本文中，我们研究了CCMDP的概括，它通过功能关系来表达对奖励的失败概率。我们得出一个约束，可以单独应用于策略中的每个状态历史，并保证满足机会约束。该方法将CCMDP中的状态分离，从而可以有效地解决大问题。然后我们引入Vulcan，它使用我们的约束来将蒙特卡罗树搜索应用于CCMDP。 Vulcan可以应用于生成整个状态空间不可行的问题，并且必须以任何方式返回策略。我们证明Vulc​​an及其变体的运行速度比线性编程方法快几十到几百倍，比基于启发式的方法快十倍以上，所有这些都不需要启发式算法，并且返回的解决方案的平均次优性大约为几个百分。最后，我们使用Vulcan来解决CCMDP中的机会约束策略，该策略在3分钟内超过$ 10 ^ {13} $状态。

##### URL
[http://arxiv.org/abs/1809.01220](http://arxiv.org/abs/1809.01220)

##### PDF
[http://arxiv.org/pdf/1809.01220](http://arxiv.org/pdf/1809.01220)

