---
layout: post
title: "Model-Free Control for Distributed Stream Data Processing using Deep Reinforcement Learning"
date: 2018-03-02 19:30:55
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Teng Li, Zhiyuan Xu, Jian Tang, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on general-purpose Distributed Stream Data Processing Systems (DSDPSs), which deal with processing of unbounded streams of continuous data at scale distributedly in real or near-real time. A fundamental problem in a DSDPS is the scheduling problem with the objective of minimizing average end-to-end tuple processing time. A widely-used solution is to distribute workload evenly over machines in the cluster in a round-robin manner, which is obviously not efficient due to lack of consideration for communication delay. Model-based approaches do not work well either due to the high complexity of the system environment. We aim to develop a novel model-free approach that can learn to well control a DSDPS from its experience rather than accurate and mathematically solvable system models, just as a human learns a skill (such as cooking, driving, swimming, etc). Specifically, we, for the first time, propose to leverage emerging Deep Reinforcement Learning (DRL) for enabling model-free control in DSDPSs; and present design, implementation and evaluation of a novel and highly effective DRL-based control framework, which minimizes average end-to-end tuple processing time by jointly learning the system environment via collecting very limited runtime statistics data and making decisions under the guidance of powerful Deep Neural Networks. To validate and evaluate the proposed framework, we implemented it based on a widely-used DSDPS, Apache Storm, and tested it with three representative applications. Extensive experimental results show 1) Compared to Storm's default scheduler and the state-of-the-art model-based method, the proposed framework reduces average tuple processing by 33.5% and 14.0% respectively on average. 2) The proposed framework can quickly reach a good scheduling solution during online learning, which justifies its practicability for online control in DSDPSs.

##### Abstract (translated by Google)
在本文中，我们专注于通用分布式流数据处理系统（DSDPS），它处理实时或近实时分布式处理无限大数据量的连续数据流。 DSDPS中的一个基本问题是调度问题，目标是最小化平均端到端元组处理时间。一种广泛使用的解决方案是以循环方式在集群中的机器上均匀分配工作负载，由于缺乏对通信延迟的考虑，这显然效率不高。由于系统环境的高度复杂性，基于模型的方法效果不佳。我们的目标是开发一种新颖的无模型方法，就像人类学习技能（如烹饪，驾驶，游泳等）一样，可以学习如何从其经验中很好地控制DSDPS，而不是准确和数学上可解的系统模型。具体而言，我们首次提出利用新兴的深度增强学习（DRL）来实现DSDPS中的无模型控制;并介绍了一种新颖高效的基于DRL的控制框架的设计，实现和评估，通过收集非常有限的运行时统计数据并在指导下进行决策，联合学习系统环境，从而最大限度地减少平均端到端元组处理时间功能强大的深度神经网络。为了验证和评估提出的框架，我们基于广泛使用的DSDPS Apache Storm实施了该框架，并使用三种代表性应用对其进行了测试。广泛的实验结果表明1）与Storm的默认调度器和最先进的基于模型的方法相比，所提出的框架平均分别将平均元组处理减少33.5％和14.0％。 2）所提出的框架可以在线学习期间快速达到一个很好的调度解决方案，这证明了DSDPS在线控制的实用性。

##### URL
[http://arxiv.org/abs/1803.01016](http://arxiv.org/abs/1803.01016)

##### PDF
[http://arxiv.org/pdf/1803.01016](http://arxiv.org/pdf/1803.01016)

