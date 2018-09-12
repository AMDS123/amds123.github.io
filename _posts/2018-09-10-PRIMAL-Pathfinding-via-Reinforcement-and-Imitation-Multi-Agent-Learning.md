---
layout: post
title: "PRIMAL: Pathfinding via Reinforcement and Imitation Multi-Agent Learning"
date: 2018-09-10 18:18:03
categories: arXiv_RO
tags: arXiv_RO
author: Guillaume Sartoretti, Justin Kerr, Yunfei Shi, Glenn Wagner, T. K. Satish Kumar, Sven Koenig, Howie Choset
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-agent path finding (MAPF) is an essential component of many large-scale, real-world robot deployments, from aerial swarms to warehouse automation to collaborative search-and-rescue. However, despite the community's continued efforts, most state-of-the-art MAPF algorithms still rely on centralized planning, and scale poorly past a few hundred agents. Such planning approaches are maladapted to real-world deployment, where noise and uncertainty often require paths to be recomputed or adapted online, which is impossible when planning times are in seconds to minutes. In this work, we present PRIMAL, a novel framework for MAPF that combines reinforcement and imitation learning to teach fully-decentralized policies, where agents reactively plan paths online in a partially-observable world while exhibiting implicit coordination. Our framework extends our previous works on distributed learning of collaborative policies by introducing demonstrations of an expert MAPF algorithm during training, as well as careful reward shaping and environment sampling. Once learned, the resulting policy can be copied onto any number of agents, and naturally scales to different team sizes and world dimensions. We present results on randomized worlds with up to 1024 agents and compare success rates against state-of-the-art MAPF algorithms. Finally, we show experimental results of the learned policies in a hybrid simulation of a factory mock-up, involving both real-world and simulated robots.

##### Abstract (translated by Google)
多代理路径查找（MAPF）是许多大型现实机器人部署的重要组成部分，从空中群体到仓库自动化再到协作搜索和救援。然而，尽管社区不断努力，但大多数最先进的MAPF算法仍然依赖于集中规划，并且在几百个代理之后规模很小。这种规划方法不适应现实世界的部署，其中噪声和不确定性通常需要在线重新计算或调整路径，这在规划时间以秒到分钟为单位时是不可能的。在这项工作中，我们提出了一个新的MAPF框架PRIMAL，它结合了强化和模仿学习来教授完全分散的政策，代理人在部分可观察的世界中反应性地规划在线路径，同时展现隐性协调。我们的框架通过在培训期间引入专家MAPF算法的演示，以及谨慎的奖励形成和环境采样，扩展了我们之前关于协作策略的分布式学习的工作。学到之后，可以将生成的策略复制到任意数量的代理上，并自然地扩展到不同的团队规模和世界维度。我们在具有多达1024个代理的随机世界中呈现结果，并将成功率与最先进的MAPF算法进行比较。最后，我们在工厂模型的混合模拟中展示了学习策略的实验结果，涉及现实世界和模拟机器人。

##### URL
[http://arxiv.org/abs/1809.03531](http://arxiv.org/abs/1809.03531)

##### PDF
[http://arxiv.org/pdf/1809.03531](http://arxiv.org/pdf/1809.03531)

