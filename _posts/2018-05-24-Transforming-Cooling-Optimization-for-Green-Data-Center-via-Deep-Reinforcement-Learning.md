---
layout: post
title: "Transforming Cooling Optimization for Green Data Center via Deep Reinforcement Learning"
date: 2018-05-24 03:13:28
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Optimization Gradient_Descent
author: Yuanlong Li, Yonggang Wen, Kyle Guan, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Cooling system plays a key role in modern data center. Developing an optimal control policy for data center cooling system is a challenging task. The prevailing approaches often rely on approximated system models that are built upon the knowledge of mechanical cooling, electrical and thermal management, which is difficult to design and may lead to sub-optimal or unstable performances. In this paper we propose to utilize the large amount of monitoring data in data center to optimize the control policy. To do so, we cast the cooling control policy design into an energy cost minimization problem with temperature constraints, and tab it into the emerging deep reinforcement learning (DRL) framework. Specifically, we propose an end-to-end neural control algorithm that is based on the actor-critic framework and the deep deterministic policy gradient (DDPG) technique. To improve the robustness of the control algorithm, we test various DRL related optimization techniques, such as recurrent decision making, discounted return, different neural network architectures, and different stochastic gradient descent algorithms, and adding additional constraints on the output of the policy network. We evaluate the proposed algorithms on the EnergyPlus simulation platform and on a real data trace collected from the National Super Computing Centre (NSCC) of Singapore. Our results show that the proposed end-to-end cooling control algorithm can achieve about 10% cooling cost saving on the simulation platform compared with a canonical two stage optimization algorithm; and it can achieve about 13.6% cooling energy saving on the NSCC data trace. Furthermore, it shows high accuracy in predicting the temperature of the racks (with mean absolute error 0.1 degree) and can control the temperature of the data center zone close to the predefined threshold with variation lower to 0.2 degree.

##### Abstract (translated by Google)
冷却系统在现代数据中心中扮演着重要角色。制定数据中心冷却系统的最佳控制策略是一项具有挑战性的任务。主流方法通常依赖于基于机械冷却，电气和热管理知识的近似系统模型，这些模型很难设计，并可能导致次优或不稳定的性能。在本文中，我们建议利用数据中心的大量监测数据来优化控制策略。为此，我们将冷却控制策略设计纳入具有温度限制的能源成本最小化问题中，并将其纳入新兴的深度强化学习（DRL）框架中。具体而言，我们提出了一种基于演员评论框架和深度确定性策略梯度（DDPG）技术的端到端神经控制算法。为了提高控制算法的鲁棒性，我们测试了各种与DRL相关的优化技术，如循环决策，折扣回报，不同的神经网络体系结构和不同的随机梯度下降算法，并在策略网络的输出上增加了额外的约束条件。我们评估在EnergyPlus仿真平台上提出的算法以及从新加坡国家超级计算中心（NSCC）收集的真实数据轨迹。我们的研究结果表明，与规范的两阶段优化算法相比，所提出的端到端冷却控制算法在模拟平台上可节约10％左右的冷却成本;在NSCC数据轨迹上可实现约13.6％的冷却节能。此外，它在预测机架温度时具有很高的准确性（平均绝对误差为0.1度），并且可以控制数据中心区域的温度接近预定义阈值，变化低于0.2度。

##### URL
[http://arxiv.org/abs/1709.05077](http://arxiv.org/abs/1709.05077)

##### PDF
[http://arxiv.org/pdf/1709.05077](http://arxiv.org/pdf/1709.05077)

