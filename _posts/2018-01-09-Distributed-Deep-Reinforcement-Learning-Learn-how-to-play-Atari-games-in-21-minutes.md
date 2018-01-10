---
layout: post
title: "Distributed Deep Reinforcement Learning: Learn how to play Atari games in 21 minutes"
date: 2018-01-09 09:39:29
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Igor Adamski, Robert Adamski, Tomasz Grel, Adam J&#x119;drych, Kamil Kaczmarek, Henryk Michalewski
mathjax: true
---

* content
{:toc}

##### Abstract
We present a study in Distributed Deep Reinforcement Learning (DDRL) focused on scalability of a state-of-the-art Deep Reinforcement Learning algorithm known as Batch Asynchronous Advantage ActorCritic (BA3C). We show that using the Adam optimization algorithm with a batch size of up to 2048 is a viable choice for carrying out large scale machine learning computations. This, combined with careful reexamination of the optimizer's hyperparameters, using synchronous training on the node level (while keeping the local, single node part of the algorithm asynchronous) and minimizing the memory footprint of the model, allowed us to achieve linear scaling for up to 64 CPU nodes. This corresponds to a training time of 21 minutes on 768 CPU cores, as opposed to 10 hours when using a single node with 24 cores achieved by a baseline single-node implementation.

##### Abstract (translated by Google)
我们提出了一个关于分布式深度增强学习（DDRL）的研究，重点关注称为批量异步优势ActorCritic（BA3C）的最先进的深度增强学习算法的可伸缩性。我们证明，使用达到2048的批量大小的Adam优化算法是进行大规模机器学习计算的可行选择。这与优化器超参数的仔细复审相结合，使用节点级的同步训练（同时保持算法的本地，单节点部分是异步的），并最小化了模型的内存占用，使我们能够实现线性缩放64个CPU节点。这相当于在768个CPU内核上的训练时间为21分钟，而使用基准单节点实现的24个内核的单个节点的训练时间则为10个小时。

##### URL
[http://arxiv.org/abs/1801.02852](http://arxiv.org/abs/1801.02852)

##### PDF
[http://arxiv.org/pdf/1801.02852](http://arxiv.org/pdf/1801.02852)

