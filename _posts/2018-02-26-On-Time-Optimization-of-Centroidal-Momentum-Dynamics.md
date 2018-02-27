---
layout: post
title: "On Time Optimization of Centroidal Momentum Dynamics"
date: 2018-02-26 03:16:02
categories: arXiv_RO
tags: arXiv_RO Attention Optimization
author: Brahayam Ponton, Alexander Herzog, Andrea Del Prete, Stefan Schaal, Ludovic Righetti
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the centroidal momentum dynamics has received substantial attention to plan dynamically consistent motions for robots with arms and legs in multi-contact scenarios. However, it is also non convex which renders any optimization approach difficult and timing is usually kept fixed in most trajectory optimization techniques to not introduce additional non convexities to the problem. But this can limit the versatility of the algorithms. In our previous work, we proposed a convex relaxation of the problem that allowed to efficiently compute momentum trajectories and contact forces. However, our approach could not minimize a desired angular momentum objective which seriously limited its applicability. Noticing that the non-convexity introduced by the time variables is of similar nature as the centroidal dynamics one, we propose two convex relaxations to the problem based on trust regions and soft constraints. The resulting approaches can compute time-optimized dynamically consistent trajectories sufficiently fast to make the approach realtime capable. The performance of the algorithm is demonstrated in several multi-contact scenarios for a humanoid robot. In particular, we show that the proposed convex relaxation of the original problem finds solutions that are consistent with the original non-convex problem and illustrate how timing optimization allows to find motion plans that would be difficult to plan with fixed timing.

##### Abstract (translated by Google)
最近，形心动量动力学已经得到了大量的关注，为多接触场景下的机器人手臂和腿的动态一致运动提供了动力学计划。然而，它也是非凸的，这使得任何优化方法都很困难，并且时序通常在大多数轨迹优化技术中保持固定，以不引入额外的非凸面问题。但是这会限制算法的多功能性。在我们以前的工作中，我们提出了凸问题的松弛问题，可以有效计算动量轨迹和接触力。然而，我们的方法不能使所需的角动量目标最小化，这严重限制了它的适用性。注意到由时间变量引入的非凸性与质心动力学类似，我们基于信任区域和软约束提出了对问题的两个凸松弛。由此产生的方法可以充分快速地计算出时间优化的动态一致轨迹，从而使这种方法具备实时性。该算法的性能表现在几个人形机器人的多接触场景中。特别是，我们证明了所提出的原始问题的凸松弛找到了与原始非凸问题一致的解，并且说明了时间优化如何能够找到运动计划，这将很难用固定的时间进行计划。

##### URL
[http://arxiv.org/abs/1709.09265](http://arxiv.org/abs/1709.09265)

##### PDF
[http://arxiv.org/pdf/1709.09265](http://arxiv.org/pdf/1709.09265)

