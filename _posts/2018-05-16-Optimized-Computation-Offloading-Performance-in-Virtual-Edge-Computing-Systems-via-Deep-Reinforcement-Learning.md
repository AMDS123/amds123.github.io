---
layout: post
title: "Optimized Computation Offloading Performance in Virtual Edge Computing Systems via Deep Reinforcement Learning"
date: 2018-05-16 06:21:02
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Xianfu Chen, Honggang Zhang, Celimuge Wu, Shiwen Mao, Yusheng Ji, Mehdi Bennis
mathjax: true
---

* content
{:toc}

##### Abstract
To improve the quality of computation experience for mobile devices, mobile-edge computing (MEC) is a promising paradigm by providing computing capabilities in close proximity within a sliced radio access network (RAN), which supports both traditional communication and MEC services. Nevertheless, the design of computation offloading policies for a virtual MEC system remains challenging. Specifically, whether to execute a computation task at the mobile device or to offload it for MEC server execution should adapt to the time-varying network dynamics. In this paper, we consider MEC for a representative mobile user in an ultra-dense sliced RAN, where multiple base stations (BSs) are available to be selected for computation offloading. The problem of solving an optimal computation offloading policy is modelled as a Markov decision process, where our objective is to maximize the long-term utility performance whereby an offloading decision is made based on the task queue state, the energy queue state as well as the channel qualities between MU and BSs. To break the curse of high dimensionality in state space, we first propose a double deep Q-network (DQN) based strategic computation offloading algorithm to learn the optimal policy without knowing a priori knowledge of network dynamics. Then motivated by the additive structure of the utility function, a Q-function decomposition technique is combined with the double DQN, which leads to novel learning algorithm for the solving of stochastic computation offloading. Numerical experiments show that our proposed learning algorithms achieve a significant improvement in computation offloading performance compared with the baseline policies.

##### Abstract (translated by Google)
为了提高移动设备的计算体验质量，移动边缘计算（MEC）是一种有前途的模式，通过在支持传统通信和MEC服务的切片无线接入网（RAN）内提供紧密接近的计算能力。尽管如此，虚拟MEC系统的计算卸载策略的设计仍然具有挑战性。具体而言，无论是在移动设备上执行计算任务还是卸载它以执行MEC服务器，都应该适应随时间变化的网络动态。在本文中，我们考虑将MEC用于超密集切片RAN中的代表性移动用户，其中可以选择多个基站（BS）用于计算卸载。解决最优计算卸载策略的问题被模拟为马尔科夫决策过程，其中我们的目标是最大化长期效用性能，由此基于任务队列状态，能量队列状态以及MU和BS之间的信道质量。为了打破状态空间中高维度的诅咒，我们首先提出一种基于双深度Q网络（DQN）的策略计算卸载算法，在不知道网络动态的先验知识的情况下学习最优策略。然后在效用函数的加性结构的驱动下，将Q函数分解技术与双DQN结合起来，为随机计算卸载求解提供了新的学习算法。数值实验表明，与基线策略相比，我们提出的学习算法在计算卸载性能方面取得了显着的改进。

##### URL
[http://arxiv.org/abs/1805.06146](http://arxiv.org/abs/1805.06146)

##### PDF
[http://arxiv.org/pdf/1805.06146](http://arxiv.org/pdf/1805.06146)

