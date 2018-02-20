---
layout: post
title: "HyP-DESPOT: A Hybrid Parallel Algorithm for Online Planning under Uncertainty"
date: 2018-02-17 08:59:56
categories: arXiv_AI
tags: arXiv_AI
author: Panpan Cai, Yuanfu Luo, David Hsu, Wee Sun Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Planning under uncertainty is critical for robust robot performance in uncertain, dynamic environments, but it incurs high computational cost. State-of-the-art online search algorithms, such as DESPOT, have vastly improved the computational efficiency of planning under uncertainty and made it a valuable tool for robotics in practice. This work takes one step further by leveraging both CPU and GPU parallelization in order to achieve near real-time online planning performance for complex tasks with large state, action, and observation spaces. Specifically, we propose Hybrid Parallel DESPOT (HyP-DESPOT), a massively parallel online planning algorithm that integrates CPU and GPU parallelism in a multi-level scheme. It performs parallel DESPOT tree search by simultaneously traversing multiple independent paths using multi-core CPUs and performs parallel Monte-Carlo simulations at the leaf nodes of the search tree using GPUs. Experimental results show that HyP-DESPOT speeds up online planning by up to several hundred times, compared with the original DESPOT algorithm, in several challenging robotic tasks in simulation.

##### Abstract (translated by Google)
在不确定的动态环境中，强大的机器人性能对不确定性下的规划至关重要，但这会导致高昂的计算成本。最先进的在线搜索算法（如DESPOT）极大地提高了不确定性下计划的计算效率，并使其成为实践中机器人技术的宝贵工具。这项工作通过利用CPU和GPU并行化进一步推进，以便为具有大型状态，动作和观察空间的复杂任务实现接近实时的在线计划性能。具体而言，我们提出混合并行DESPOT（HyP-DESPOT），一种大规模并行在线规划算法，将CPU和GPU并行性集成到一个多级方案中。它通过使用多核CPU同时遍历多个独立路径执行并行DESPOT树搜索，并使用GPU在搜索树的叶节点执行并行Monte-Carlo仿真。实验结果表明，HyP-DESPOT在模拟的几个具有挑战性的机器人任务中，与原始DESPOT算法相比，在线规划速度提高了几百倍。

##### URL
[http://arxiv.org/abs/1802.06215](http://arxiv.org/abs/1802.06215)

##### PDF
[http://arxiv.org/pdf/1802.06215](http://arxiv.org/pdf/1802.06215)

