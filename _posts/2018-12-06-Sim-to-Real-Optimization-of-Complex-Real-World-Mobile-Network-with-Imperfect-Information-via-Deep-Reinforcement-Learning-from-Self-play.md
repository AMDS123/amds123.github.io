---
layout: post
title: "Sim-to-Real Optimization of Complex Real World Mobile Network with Imperfect Information via Deep Reinforcement Learning from Self-play"
date: 2018-12-06 12:09:16
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning CNN Transfer_Learning Optimization
author: Yongxi Tan, Jin Yang, Xin Chen, Qitao Song, Yunjun Chen, Zhangxiang Ye, Zhenqiang Su
mathjax: true
---

* content
{:toc}

##### Abstract
Mobile network that millions of people use every day is one of the most complex systems in the world. Optimization of mobile network to meet exploding customer demand and reduce capital/operation expenditures poses great challenges. Despite recent progress, application of deep reinforcement learning (DRL) to complex real world problem still remains unsolved, given data scarcity, partial observability, risk and complex rules/dynamics in real world, as well as the huge reality gap between simulation and real world. To bridge the reality gap, we introduce a Sim-to-Real framework to directly transfer learning from simulation to real world via graph convolutional neural network (CNN) - by abstracting partially observable mobile network into graph, then distilling domain-variant irregular graph into domain-invariant tensor in locally Euclidean space as input to CNN -, domain randomization and multi-task learning. We use a novel self-play mechanism to encourage competition among DRL agents for best record on multiple tasks via simulated annealing, just like athletes compete for world record in decathlon. We also propose a decentralized multi-agent, competitive and cooperative DRL method to coordinate the actions of multi-cells to maximize global reward and minimize negative impact to neighbor cells. Using 6 field trials on commercial mobile networks, we demonstrate for the first time that a DRL agent can successfully transfer learning from simulation to complex real world problem with imperfect information, complex rules/dynamics, huge state/action space, and multi-agent interactions, without any training in the real world.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.06416](http://arxiv.org/abs/1802.06416)

##### PDF
[http://arxiv.org/pdf/1802.06416](http://arxiv.org/pdf/1802.06416)

