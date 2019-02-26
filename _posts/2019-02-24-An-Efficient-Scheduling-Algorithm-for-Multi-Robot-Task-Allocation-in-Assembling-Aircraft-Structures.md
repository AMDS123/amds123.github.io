---
layout: post
title: "An Efficient Scheduling Algorithm for Multi-Robot Task Allocation in Assembling Aircraft Structures"
date: 2019-02-24 07:38:22
categories: arXiv_RO
tags: arXiv_RO
author: Veniamin Tereshchuk, John Stewart, Nikolay Bykov, Samuel Pedigo, Santosh Devasia, Ashis G. Banerjee
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient utilization of cooperating robots in the assembly of aircraft structures relies on balancing the workload of the robots and ensuring collision-free scheduling. We cast this problem as that of allocating a large number of repetitive assembly tasks, such as drilling holes and installing fasteners, among multiple robots. Such task allocation is often formulated as a Traveling Salesman Problem (TSP), which is NP-hard, implying that computing an exactly optimal solution is computationally prohibitive for real-world applications. The problem complexity is further exacerbated by intermittent robot failures necessitating real-time task reallocation. In this letter, we present an efficient method that exploits workpart geometry and problem structure to initially generate balanced and conflict-free robot schedules under nominal conditions. Subsequently, we deal with the failures by allowing the robots to first complete their nominal schedules and then employing a market-based optimizer to allocate the leftover tasks. Results show an improvement of 13% in schedule efficiencies as compared to a greedy multi-agent scheduler on a four robot system, which is especially promising for aircraft assembly processes that take many hours to complete. Moreover, the computation times are similar and small, typically less than one second.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08905](http://arxiv.org/abs/1902.08905)

##### PDF
[http://arxiv.org/pdf/1902.08905](http://arxiv.org/pdf/1902.08905)

