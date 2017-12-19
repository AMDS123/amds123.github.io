---
layout: post
title: "Ray: A Distributed Framework for Emerging AI Applications"
date: 2017-12-16 01:29:49
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Philipp Moritz, Robert Nishihara, Stephanie Wang, Alexey Tumanov, Richard Liaw, Eric Liang, William Paul, Michael I. Jordan, Ion Stoica
mathjax: true
---

* content
{:toc}

##### Abstract
The next generation of AI applications will continuously interact with the environment and learn from these interactions. These applications impose new and demanding systems requirements, both in terms of performance and flexibility. In this paper, we consider these requirements and present Ray---a distributed system to address them. Ray implements a dynamic task graph computation model that supports both the task-parallel and the actor programming models. To meet the performance requirements of AI applications, we propose an architecture that logically centralizes the system's control state using a sharded storage system and a novel bottom-up distributed scheduler. In our experiments, we demonstrate sub-millisecond remote task latencies and linear throughput scaling beyond 1.8 million tasks per second. We empirically validate that Ray speeds up challenging benchmarks and serves as both a natural and performant fit for an emerging class of reinforcement learning applications and algorithms.

##### Abstract (translated by Google)
下一代AI应用程序将不断与环境交互，并从这些交互中学习。这些应用程序在性能和灵活性方面提出了新的和苛刻的系统要求。在本文中，我们考虑这些要求并提出Ray ---分布式系统来解决它们。 Ray实现了一个动态任务图计算模型，支持任务并行和参与者编程模型。为了满足人工智能应用的性能要求，我们提出了一种架构，使用分片存储系统和新颖的自下而上的分布式调度器，在逻辑上集中了系统的控制状态。在我们的实验中，我们展示了亚毫秒的远程任务延迟和线性吞吐量，每秒超过180万个任务。我们凭经验验证了Ray加速了具有挑战性的基准测试，同时也是适合新兴的一类强化学习应用和算法的自然和高性能表现。

##### URL
[http://arxiv.org/abs/1712.05889](http://arxiv.org/abs/1712.05889)

##### PDF
[http://arxiv.org/pdf/1712.05889](http://arxiv.org/pdf/1712.05889)

