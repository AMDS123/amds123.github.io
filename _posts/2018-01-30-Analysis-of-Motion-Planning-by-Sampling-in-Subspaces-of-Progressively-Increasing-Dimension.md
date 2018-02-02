---
layout: post
title: "Analysis of Motion Planning by Sampling in Subspaces of Progressively Increasing Dimension"
date: 2018-01-30 22:01:35
categories: arXiv_RO
tags: arXiv_RO
author: Marios P. Xanthidis, Joel M. Esposito, Ioannis Rekleitis, Jason M. O&#x27;Kane
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the performance advantages of modern sampling-based motion planners, solving high dimensional planning problems in near real-time remains a challenge. Applications include hyper-redundant manipulators, snake-like and humanoid robots. Based on the intuition that many of these problem instances do not require the robots to exercise every degree of freedom independently, we introduce an enhancement to popular sampling-based planning algorithms aimed at circumventing the exponential dependence on dimensionality. We propose beginning the search in a lower dimensional subspace of the configuration space in the hopes that a simple solution will be found quickly. After a certain number of samples are generated, if no solution is found, we increase the dimension of the search subspace by one and continue sampling in the higher dimensional subspace. In the worst case, the search subspace expands to include the full configuration space - making the completeness properties identical to the underlying sampling-based planer. Our experiments comparing the enhanced and traditional version of RRT, RRT-Connect, and BidirectionalT-RRT on both a planar hyper-redundant manipulator and the Baxter humanoid robot indicate that a solution is typically found much faster using this approach and the run time appears to be less sensitive to the dimension of the full configuration space. We explore important implementation issues in the sampling process and discuss its limitations.

##### Abstract (translated by Google)
尽管现代采样运动规划者具有性能优势，但近乎实时地解决高维计划问题依然是一个挑战。应用包括超冗余操纵器，蛇形和仿人机器人。基于许多这些问题实例并不需要机器人独立行使每一个自由度的直觉，我们引入了一个基于抽样的规划算法的改进，以规避维数的指数依赖。我们建议在配置空间的较低维子空间中开始搜索，希望快速找到一个简单的解决方案。在产生了一定数量的样本之后，如果没有找到解，我们将搜索子空间的维数增加1，并在高维子空间中继续采样。在最坏的情况下，搜索子空间扩展为包括完整的配置空间 - 使完整性属性与基础采样刨床相同。我们在平面超冗余操纵器和Baxter仿人机器人上比较了RRT，RRT-Connect和BidirectionalT-RRT的增强和传统版本的实验表明，使用这种方法通常发现解决方案快得多，并且运行时间似乎对整个配置空间的维度不那么敏感。我们探讨抽样过程中的重要实施问题并讨论其局限性。

##### URL
[http://arxiv.org/abs/1802.00328](http://arxiv.org/abs/1802.00328)

##### PDF
[http://arxiv.org/pdf/1802.00328](http://arxiv.org/pdf/1802.00328)

