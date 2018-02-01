---
layout: post
title: "A Single-Planner Approach to Multi-Modal Humanoid Mobility"
date: 2018-01-30 21:02:47
categories: arXiv_RO
tags: arXiv_RO
author: Andrew Dornbush, Karthik Vijayakumar, Sameer Bardapurkar, Fahad Islam, Maxim Likhachev
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present an approach to planning for humanoid mobility. Humanoid mobility is a challenging problem, as the configuration space for a humanoid robot is intractably large, especially if the robot is capable of performing many types of locomotion. For example, a humanoid robot may be able to perform such tasks as bipedal walking, crawling, and climbing. Our approach is to plan for all these tasks within a single search process. This allows the search to reason about all the capabilities of the robot at any point, and to derive the complete solution such that the plan is guaranteed to be feasible. A key observation is that we often can roughly decompose a mobility task into a sequence of smaller tasks, and focus planning efforts to reason over much smaller search spaces. To this end, we leverage the results of a recently developed framework for planning with adaptive dimensionality, and incorporate the capabilities of available controllers directly into the planning process. The resulting planner can also be run in an interleaved fashion alongside execution so that time spent idle is much reduced.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个计划人形流动的方法。人形机动性是一个具有挑战性的问题，因为类人机器人的配置空间是难以驾驭的，特别是如果机器人能够执行多种类型的运动。例如，类人机器人可以执行诸如双足步行，爬行和攀爬等任务。我们的方法是在一个搜索过程中规划所有这些任务。这使得搜索能够在任何时候对机器人的所有功能进行推理，并导出完整的解决方案，从而保证计划的可行性。一个关键的观察是，我们经常可以粗略地将移动性任务分解成一系列较小的任务，并将计划工作的重点放在小得多的搜索空间上。为此，我们利用最近开发的具有自适应维度的规划框架的结果，并将可用控制器的功能直接纳入规划过程。生成的规划器也可以在执行的同时以交错的方式运行，这样闲置的时间大大减少。

##### URL
[http://arxiv.org/abs/1801.10225](http://arxiv.org/abs/1801.10225)

##### PDF
[http://arxiv.org/pdf/1801.10225](http://arxiv.org/pdf/1801.10225)

