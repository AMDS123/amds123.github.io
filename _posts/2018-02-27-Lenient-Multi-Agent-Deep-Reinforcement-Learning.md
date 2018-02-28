---
layout: post
title: "Lenient Multi-Agent Deep Reinforcement Learning"
date: 2018-02-27 09:36:29
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Gregory Palmer, Karl Tuyls, Daan Bloembergen, Rahul Savani
mathjax: true
---

* content
{:toc}

##### Abstract
Much of the success of single agent deep reinforcement learning (DRL) in recent years can be attributed to the use of experience replay memories (ERM), which allow Deep Q-Networks (DQNs) to be trained efficiently through sampling stored state transitions. However, care is required when using ERMs for multi-agent deep reinforcement learning (MA-DRL), as stored transitions can become outdated because agents update their policies in parallel [11]. In this work we apply leniency [23] to MA-DRL. Lenient agents map state-action pairs to decaying temperature values that control the amount of leniency applied towards negative policy updates that are sampled from the ERM. This introduces optimism in the value-function update, and has been shown to facilitate cooperation in tabular fully-cooperative multi-agent reinforcement learning problems. We evaluate our Lenient-DQN (LDQN) empirically against the related Hysteretic-DQN (HDQN) algorithm [22] as well as a modified version we call scheduled-HDQN, that uses average reward learning near terminal states. Evaluations take place in extended variations of the Coordinated Multi-Agent Object Transportation Problem (CMOTP) [8] which include fully-cooperative sub-tasks and stochastic rewards. We find that LDQN agents are more likely to converge to the optimal policy in a stochastic reward CMOTP compared to standard and scheduled-HDQN agents.

##### Abstract (translated by Google)
近年来，单一代理深度强化学习（DRL）的成功很大程度上归功于使用了经验重播记忆（ERM），这种记忆允许深度Q网络（DQN）通过对存储状态转换进行采样来高效地进行训练。然而，当使用ERMs进行多代理深度强化学习（MA-DRL）时需要小心，因为代理并行更新其策略[11]，因此存储的转换可能会过时。在这项工作中，我们将宽大[23]应用于MA-DRL。宽松代理将状态 - 行为对映射为衰减温度值，以控制从ERM采样的负面策略更新所应用的宽松量。这引入了对价值函数更新的乐观态度，并且已被证明有助于表格式全合作多智能体强化学习问题的合作。我们根据相关的Hysteretic-DQN（HDQN）算法[22]以及我们称之为预定HDQN的修改版本对经验性Lenient-DQN（LDQN）进行评估，该算法使用终端状态附近的平均奖励学习。评估发生在协调多智能体对象运输问题（CMOTP）[8]的扩展变体中，其中包括完全合作的子任务和随机奖励。我们发现与标准和定期HDQN代理相比，LDQN代理更有可能在一个随机奖励CMOTP中收敛到最优策略。

##### URL
[http://arxiv.org/abs/1707.04402](http://arxiv.org/abs/1707.04402)

##### PDF
[http://arxiv.org/pdf/1707.04402](http://arxiv.org/pdf/1707.04402)

