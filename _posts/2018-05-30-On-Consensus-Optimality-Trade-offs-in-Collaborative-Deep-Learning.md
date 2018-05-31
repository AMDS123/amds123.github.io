---
layout: post
title: "On Consensus-Optimality Trade-offs in Collaborative Deep Learning"
date: 2018-05-30 17:59:24
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Zhanhong Jiang, Aditya Balu, Chinmay Hegde, Soumik Sarkar
mathjax: true
---

* content
{:toc}

##### Abstract
In distributed machine learning, where agents collaboratively learn from diverse private data sets, there is a fundamental tension between consensus and optimality. In this paper, we build on recent algorithmic progresses in distributed deep learning to explore various consensus-optimality trade-offs over a fixed communication topology. First, we propose the incremental consensus-based distributed SGD (i-CDSGD) algorithm, which involves multiple consensus steps (where each agent communicates information with its neighbors) within each SGD iteration. Second, we propose the generalized consensus-based distributed SGD (g-CDSGD) algorithm that enables us to navigate the full spectrum from complete consensus (all agents agree) to complete disagreement (each agent converges to individual model parameters). We analytically establish convergence of the proposed algorithms for strongly convex and nonconvex objective functions; we also analyze the momentum variants of the algorithms for the strongly convex case. We support our algorithms via numerical experiments, and demonstrate significant improvements over existing methods for collaborative deep learning.

##### Abstract (translated by Google)
在分布式机器学习中，代理人通过不同的私人数据集进行协作学习，在共识和最优化之间存在着根本的紧张关系。在本文中，我们基于最近在分布式深度学习中的算法进展，探索固定通信拓扑中的各种共识 - 最优折衷。首先，我们提出了基于增量共识的分布式SGD（i-CDSGD）算法，该算法在每次SGD迭代中涉及多个共识步骤（每个代理与其邻居进行信息交流）。其次，我们提出了广义的基于共识的分布式SGD（g-CDSGD）算法，该算法使我们能够从完全一致（所有代理商同意）到完全不一致（每个代理商收敛到单个模型参数）的全部频谱中。我们通过分析建立了强凸和非凸目标函数的算法的收敛性;我们还分析了强凸面情况下算法的动量变量。我们通过数值实验支持我们的算法，并且证明与现有的协同深度学习方法相比有了显着的改进

##### URL
[https://arxiv.org/abs/1805.12120](https://arxiv.org/abs/1805.12120)

##### PDF
[https://arxiv.org/pdf/1805.12120](https://arxiv.org/pdf/1805.12120)

