---
layout: post
title: "IMPALA: Scalable Distributed Deep-RL with Importance Weighted Actor-Learner Architectures"
date: 2018-02-05 18:47:30
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Lasse Espeholt, Hubert Soyer, Remi Munos, Karen Simonyan, Volodymir Mnih, Tom Ward, Yotam Doron, Vlad Firoiu, Tim Harley, Iain Dunning, Shane Legg, Koray Kavukcuoglu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we aim to solve a large collection of tasks using a single reinforcement learning agent with a single set of parameters. A key challenge is to handle the increased amount of data and extended training time, which is already a problem in single task learning. We have developed a new distributed agent IMPALA (Importance-Weighted Actor Learner Architecture) that can scale to thousands of machines and achieve a throughput rate of 250,000 frames per second. We achieve stable learning at high throughput by combining decoupled acting and learning with a novel off-policy correction method called V-trace, which was critical for achieving learning stability. We demonstrate the effectiveness of IMPALA for multi-task reinforcement learning on DMLab-30 (a set of 30 tasks from the DeepMind Lab environment (Beattie et al., 2016)) and Atari-57 (all available Atari games in Arcade Learning Environment (Bellemare et al., 2013a)). Our results show that IMPALA is able to achieve better performance than previous agents, use less data and crucially exhibits positive transfer between tasks as a result of its multi-task approach.

##### Abstract (translated by Google)
在这项工作中，我们的目标是使用单一的强化学习代理和一组参数来解决大量的任务。一个关键的挑战是处理数据量增加和延长训练时间，这在单一任务学习中已经是一个问题。我们开发了一种新的分布式代理IMPALA（重要性加权的学习者架构），可以扩展到数千台机器，每秒吞吐量达到25万帧。我们通过将解耦的动作和学习与一种叫做V-trace的新型的不对称校正方法相结合，实现了高通量的稳定学习，这对于实现学习的稳定性至关重要。我们展示了IMPALA在DMLab-30（来自DeepMind Lab环境的一组30个任务（Beattie等人，2016））和Atari-57（所有Atari游戏在街机学习环境中的多任务强化学习的有效性Bellemare等，2013a））。我们的研究结果表明，IMPALA能够实现比以前的代理更好的性能，使用更少的数据，并且由于其多任务方法而在关键任务之间展现出积极的转移。

##### URL
[http://arxiv.org/abs/1802.01561](http://arxiv.org/abs/1802.01561)

##### PDF
[http://arxiv.org/pdf/1802.01561](http://arxiv.org/pdf/1802.01561)

