---
layout: post
title: "Multi-Modal Active Perception for Information Gathering in Science Missions"
date: 2017-12-28 00:20:47
categories: arXiv_RO
tags: arXiv_RO Knowledge Inference
author: Akash Arora, P. Michael Furlong, Robert Fitch, Salah Sukkarieh, Terrence Fong
mathjax: true
---

* content
{:toc}

##### Abstract
Robotic science missions in remote environments, such as deep ocean and outer space, can involve studying phenomena that cannot directly be observed using on-board sensors but must be deduced by combining measurements of correlated variables with domain knowledge. Traditionally, in such missions, robots passively gather data along prescribed paths, while inference, path planning, and other high level decision making is largely performed by a supervisory science team. However, communication constraints hinder these processes, and hence the rate of scientific progress. This paper presents an active perception approach that aims to reduce robots' reliance on human supervision and improve science productivity by encoding scientists' domain knowledge and decision making process on-board. We use Bayesian networks to compactly model critical aspects of scientific knowledge while remaining robust to observation and modeling uncertainty. We then formulate path planning and sensor scheduling as an information gain maximization problem, and propose a sampling-based solution based on Monte Carlo tree search to plan informative sensing actions which exploit the knowledge encoded in the network. The computational complexity of our framework does not grow with the number of observations taken and allows long horizon planning in an anytime manner, making it highly applicable to field robotics. Simulation results show statistically significant performance improvements over baseline methods, and we validate the practicality of our approach through both hardware experiments and simulated experiments with field data gathered during the NASA Mojave Volatiles Prospector science expedition.

##### Abstract (translated by Google)
在遥远的环境中，如深海和外太空的机器人科学任务可能涉及到使用机载传感器无法直接观察到的现象，但必须通过将相关变量的测量与领域知识相结合来推断。传统上，在这样的任务中，机器人被动地收集数据沿规定的路径，而推理，路径规划和其他高层决策主要由监督科学小组来执行。然而，传播限制阻碍了这些进程，从而影响了科学进步的速度。本文提出了一种主动感知方法，旨在减少机器人对人类监督的依赖，并通过对科学家的领域知识和决策过程进行编码来提高科学生产力。我们使用贝叶斯网络对科学知识的关键方面进行紧凑建模，同时对观察和建模不确定性保持强大。然后，将路径规划和传感器调度作为信息增益最大化问题，提出了一种基于蒙特卡罗树搜索的基于采样的解决方案，以规划利用网络编码知识的信息感知行为。我们框架的计算复杂度不会随着观察次数的增加而增长，并允许随时进行长时间的规划，使其非常适用于现场机器人。仿真结果显示，与基线方法相比，性能有显着的改善，我们通过硬件实验和模拟实验，验证了我们方法的实用性，并在NASA莫哈韦沙漠探测器科学考察期间收集了实地数据。

##### URL
[https://arxiv.org/abs/1712.09716](https://arxiv.org/abs/1712.09716)

##### PDF
[https://arxiv.org/pdf/1712.09716](https://arxiv.org/pdf/1712.09716)

