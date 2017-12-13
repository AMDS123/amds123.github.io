---
layout: post
title: "Determining Majority in Networks with Local Interactions and very Small Local Memory"
date: 2014-04-30 10:29:46
categories: arXiv_CV
tags: arXiv_CV
author: George B. Mertzios, Sotiris E. Nikoletseas, Christoforos L. Raptopoulos, Paul G. Spirakis
mathjax: true
---

* content
{:toc}

##### Abstract
We study here the problem of determining the majority type in an arbitrary connected network, each vertex of which has initially two possible types. The vertices may have a few additional possible states and can interact in pairs only if they share an edge. Any (population) protocol is required to stabilize in the initial majority. We first present and analyze a protocol with 4 states per vertex that always computes the initial majority value, under any fair scheduler. As we prove, this protocol is optimal, in the sense that there is no population protocol that always computes majority with fewer than 4 states per vertex. However this does not rule out the existence of a protocol with 3 states per vertex that is correct with high probability. To this end, we examine a very natural majority protocol with 3 states per vertex, introduced in [Angluin et al. 2008] where its performance has been analyzed for the clique graph. We study the performance of this protocol in arbitrary networks. We prove that, when the two initial states are put uniformly at random on the vertices, this protocol converges to the initial majority with probability higher than the probability of converging to the initial minority. In contrast, we present an infinite family of graphs, on which the protocol can fail whp, even when the difference between the initial majority and the initial minority is $n - \Theta(\ln{n})$. We also present another infinite family of graphs in which the protocol of Angluin et al. takes an expected exponential time to converge. These two negative results build upon a very positive result concerning the robustness of the protocol on the clique. Surprisingly, the resistance of the clique to failure causes the failure in general graphs. Our techniques use new domination and coupling arguments for suitably defined processes whose dynamics capture the antagonism between the states involved.

##### Abstract (translated by Google)
我们在这里研究确定在任意连接网络中的多数类型的问题，其中每个顶点最初有两种可能的类型。顶点可能有一些额外的可能的状态，并且只有在共享一个边时才能成对交互。任何（人口）协议都需要稳定在最初的多数。我们首先提出并分析一个协议，每个顶点具有4个状态，总是在任何公平调度器下计算初始多数值。正如我们所证明的那样，这个协议是最优的，因为没有人口协议总是用每个顶点少于4个状态计算多数。然而这并不排除每个顶点具有3个状态的协议的存在是高概率正确的。为此，我们研究了一个非常自然的多数协议，每个顶点有三个状态，在[Angluin et al。 2008]，其分析表现为集团图表。我们研究这个协议在任意网络中的性能。证明了当两个初始状态在顶点上随机均匀分布时，该协议收敛到最初的多数，概率比收敛到最初的少数几率高。相比之下，我们提出了一个无限的图族，即使最初的多数与最初的少数之间的差异是$ n  -  \ Theta（\ ln {n}）$，协议也可能会失败。我们还提出了另一个无限的图表族，其中Angluin et al。需要一个预期的指数时间来收敛。这两个负面的结果是关于该集团议定书的稳健性的一个非常积极的结果。令人惊讶的是，集团对失败的抵抗导致了一般图形的失败。我们的技术使用新的控制和耦合参数来定义合适的过程，其动态捕捉所涉及的状态之间的对抗。

##### URL
[https://arxiv.org/abs/1404.7671](https://arxiv.org/abs/1404.7671)

##### PDF
[https://arxiv.org/pdf/1404.7671](https://arxiv.org/pdf/1404.7671)

