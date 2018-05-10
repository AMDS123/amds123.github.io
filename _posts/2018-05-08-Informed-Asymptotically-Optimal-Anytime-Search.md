---
layout: post
title: "Informed Asymptotically Optimal Anytime Search"
date: 2018-05-08 22:05:17
categories: arXiv_RO
tags: arXiv_RO
author: Jonathan D. Gammell, Timothy D. Barfoot, Siddhartha S. Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
Path planning in robotics often requires finding high-quality solutions to continuously valued and/or high-dimensional problems. These problems are challenging and most planning algorithms instead solve simplified approximations. Popular approximations include graphs and random samples, as respectively used by informed graph-based searches and anytime sampling-based planners. Informed graph-based searches, such as A*, traditionally use heuristics to search a priori graphs in order of potential solution quality. This makes their search efficient but leaves their performance dependent on the chosen approximation. If its resolution is too low then they may not find a (suitable) solution but if it is too high then they may take a prohibitively long time to do so. Anytime sampling-based planners, such as RRT*, traditionally use random sampling to approximate the problem domain incrementally. This allows them to increase resolution until a suitable solution is found but makes their search dependent on the order of approximation. Arbitrary sequences of random samples expand the approximation in every direction and fill the problem domain but may be prohibitively inefficient at containing a solution. This paper unifies and extends these two approaches to develop Batch Informed Trees (BIT*), an informed, anytime sampling-based planner. BIT* solves continuous path planning problems efficiently by using sampling and heuristics to alternately approximate and search the problem domain. Its search is ordered by potential solution quality, as in A*, and its approximation improves indefinitely with additional computational time, as in RRT*. It is shown analytically to be almost-surely asymptotically optimal and experimentally to outperform existing sampling-based planners, especially on high-dimensional planning problems.

##### Abstract (translated by Google)
机器人技术中的路径规划通常需要寻找高质量的解决方案来解决连续的价值和/或高维问题。这些问题是具有挑战性的，大多数规划算法反而会解决简化的近似。常用的近似值包括图形和随机样本，分别由知情图形搜索和随时抽样计划人员使用。传统上，基于图形的搜索（例如A *）使用启发式方法按潜在解决方案质量的顺序搜索先验图。这使得他们的搜索效率很高，但其性能依赖于所选的近似值。如果它的分辨率太低，那么他们可能找不到（适当的）解决方案，但如果它太高，那么它们可能需要很长的时间才能完成。任何时候基于抽样的规划者，例如RRT *，传统上都是使用随机抽样来逐步逼近问题域。这允许他们增加分辨率，直到找到合适的解决方案，但是使得他们的搜索取决于近似的顺序。随机样本的任意序列扩展了每个方向的近似值，并填充问题域，但在包含解决方案时可能过于低效。本文结合并扩展了这两种方法来开发批量知情树（BIT *），这是一个随时知情的，随时抽样的规划者。 BIT *通过采样和启发式方法交替地近似和搜索问题域，从而有效地解决了连续路径规划问题。其搜索按潜在解决方案质量进行排序，如A *所示，并且其近似值随着计算时间的增加而无限增加，如在RRT *中。分析表明，几乎肯定是渐近最优和实验性的，以超越现有的抽样计划者，尤其是高维计划问题。

##### URL
[http://arxiv.org/abs/1707.01888](http://arxiv.org/abs/1707.01888)

##### PDF
[http://arxiv.org/pdf/1707.01888](http://arxiv.org/pdf/1707.01888)

