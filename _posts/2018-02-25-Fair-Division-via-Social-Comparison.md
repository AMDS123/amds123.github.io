---
layout: post
title: "Fair Division via Social Comparison"
date: 2018-02-25 19:16:36
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Rediet Abebe, Jon Kleinberg, David Parkes
mathjax: true
---

* content
{:toc}

##### Abstract
In the classical cake cutting problem, a resource must be divided among agents with different utilities so that each agent believes they have received a fair share of the resource relative to the other agents. We introduce a variant of the problem in which we model an underlying social network on the agents with a graph, and agents only evaluate their shares relative to their neighbors' in the network. This formulation captures many situations in which it is unrealistic to assume a global view, and also exposes interesting phenomena in the original problem. 
 Specifically, we say an allocation is locally envy-free if no agent envies a neighbor's allocation and locally proportional if each agent values her own allocation as much as the average value of her neighbor's allocations, with the former implying the latter. While global envy-freeness implies local envy-freeness, global proportionality does not imply local proportionality, or vice versa. A general result is that for any two distinct graphs on the same set of nodes and an allocation, there exists a set of valuation functions such that the allocation is locally proportional on one but not the other. 
 We fully characterize the set of graphs for which an oblivious single-cutter protocol-- a protocol that uses a single agent to cut the cake into pieces --admits a bounded protocol with $O(n^2)$ query complexity for locally envy-free allocations in the Robertson-Webb model. We also consider the price of envy-freeness, which compares the total utility of an optimal allocation to the best utility of an allocation that is envy-free. We show that a lower bound of $\Omega(\sqrt{n})$ on the price of envy-freeness for global allocations in fact holds for local envy-freeness in any connected undirected graph. Thus, sparse graphs surprisingly do not provide more flexibility with respect to the quality of envy-free allocations.

##### Abstract (translated by Google)
在传统的蛋糕切割问题中，资源必须在具有不同效用的代理中分配，以便每个代理相信他们已经获得了相对于其他代理的公平份额。我们引入了一个问题的变体，我们用一个图对代理人的基础社交网络进行建模，代理人只评估他们在网络中相对于他们邻居的份额。这种表述捕捉了很多情况，假设全球视图是不现实的，并且在原始问题中也暴露出有趣的现象。
 具体而言，如果没有代理人羡慕邻居的分配，并且如果每个代理人将她自己的分配与其邻居的分配的平均值相同，则分配本地嫉妒，前者意味着后者。虽然全球嫉妒意味着本地嫉妒，但全球相称并不意味着当地的相称性，反之亦然。通常的结果是，对于同一组节点和分配中的任何两个不同的图，存在一组估值函数，使得分配在一个而不是另一个上与局部成比例。
 我们充分描述了一套不经意的单刀片协议 - 一种使用单一代理将协议片断成块的协议 - 提供了一个带有$ O（n ^ 2）$查询复杂性的有界协议，用于本地嫉妒Robertson-Webb模型中的免费分配。我们还考虑了嫉妒的价格，它比较了最优分配的总效用和嫉妒分配的最佳效用。我们表明，对于全局分配的嫉妒免费价格，$ \ Omega（\ sqrt {n}）$的下界实际上适用于任何连接的无向图中的局部嫉妒。因此，稀疏图表令人惊讶地不提供更多的嫉妒分配质量方面的灵活性。

##### URL
[http://arxiv.org/abs/1611.06589](http://arxiv.org/abs/1611.06589)

##### PDF
[http://arxiv.org/pdf/1611.06589](http://arxiv.org/pdf/1611.06589)

