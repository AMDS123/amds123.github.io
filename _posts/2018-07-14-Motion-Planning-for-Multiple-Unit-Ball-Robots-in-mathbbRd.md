---
layout: post
title: "Motion Planning for Multiple Unit-Ball Robots in $mathbb{R}^d$"
date: 2018-07-14 18:49:56
categories: arXiv_RO
tags: arXiv_RO
author: Israela Solomon, Dan Halperin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a decoupled algorithm for motion planning for a collection of unit-balls moving among polyhedral obstacles in $\mathbb{R}^d$, for any $d \ge 2$. We assume that the robots have revolving areas in the vicinity of their start and target positions: Revolving areas are regions where robots can maneuver in order to give way to another moving robot. Given that this assumption is fulfilled, the algorithm is complete, namely it is guaranteed to find a solution or report that none exists. A key goal in our design is to make the revolving areas as economical as possible and in particular to allow different revolving areas to overlap. This makes the analysis rather involved but in return makes the algorithm conceptually fairly simple. We show that for the case of $m$ unit-discs moving among polygonal obstacles of total complexity $n$ in $\mathbb{R}^2$, the algorithm can be executed in $O(n^2m + m(m+n)\log(m+n))$ time. We implemented the algorithm for this case and tested it on several scenarios, for which we show experimental results for up to $1000$ robots. Finally, we address the problem of choosing the order of execution of the paths in decoupled algorithms that locally solve interferences and show that finding the optimal order of execution is NP-hard. This motivated us to develop a heuristic for choosing the order; we describe the heuristic and demonstrate its effectiveness in certain scenarios.

##### Abstract (translated by Google)
我们提出了一种解耦算法，用于在$ \ mathbb {R} ^ d $中的多面体障碍中移动的单位球集合的运动规划，对于任何$ d \ ge 2 $。我们假设机器人在其起始位置和目标位置附近具有旋转区域：旋转区域是机器人可以操纵的区域，以便让位于另一个移动机器人。在满足该假设的情况下，算法是完整的，即保证找到不存在的解决方案或报告。我们设计的一个关键目标是使旋转区域尽可能经济，特别是允许不同的旋转区域重叠。这使分析相当复杂，但作为回报，算法在概念上相当简单。我们表明，对于$ m $ unit-disc在$ \ mathbb {R} ^ 2 $中的总复杂度$ n $的多边形障碍物之间移动的情况，该算法可以在$ O（n ^ 2m + m（m）中执行+ n）\ log（m + n））$ time。我们针对这种情况实施了算法并在几种情况下对其进行了测试，为此我们展示了最高$ 1000 $机器人的实验结果。最后，我们解决了在局部解决干扰的解耦算法中选择路径执行顺序的问题，并表明找到最佳执行顺序是NP难的。这促使我们开发了一种选择顺序的启发式方法;我们描述启发式并在某些场景中证明其有效性。

##### URL
[http://arxiv.org/abs/1807.05428](http://arxiv.org/abs/1807.05428)

##### PDF
[http://arxiv.org/pdf/1807.05428](http://arxiv.org/pdf/1807.05428)

