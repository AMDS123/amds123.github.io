---
layout: post
title: "Deep Reinforcement Learning for Traffic Light Control in Vehicular Networks"
date: 2018-03-29 15:24:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning CNN
author: Xiaoyuan Liang, Xunsheng Du, Guiling Wang, Zhu Han
mathjax: true
---

* content
{:toc}

##### Abstract
Existing inefficient traffic light control causes numerous problems, such as long delay and waste of energy. To improve efficiency, taking real-time traffic information as an input and dynamically adjusting the traffic light duration accordingly is a must. In terms of how to dynamically adjust traffic signals' duration, existing works either split the traffic signal into equal duration or extract limited traffic information from the real data. In this paper, we study how to decide the traffic signals' duration based on the collected data from different sensors and vehicular networks. We propose a deep reinforcement learning model to control the traffic light. In the model, we quantify the complex traffic scenario as states by collecting data and dividing the whole intersection into small grids. The timing changes of a traffic light are the actions, which are modeled as a high-dimension Markov decision process. The reward is the cumulative waiting time difference between two cycles. To solve the model, a convolutional neural network is employed to map the states to rewards. The proposed model is composed of several components to improve the performance, such as dueling network, target network, double Q-learning network, and prioritized experience replay. We evaluate our model via simulation in the Simulation of Urban MObility (SUMO) in a vehicular network, and the simulation results show the efficiency of our model in controlling traffic lights.

##### Abstract (translated by Google)
现有的低效率的交通灯控制会导致很多问题，例如长时间延迟和能源浪费。为了提高效率，以实时交通信息作为输入并相应地动态调整交通灯持续时间是必须的。在如何动态调整交通信号持续时间方面，现有的作品要么将交通信号分成相等的时间，要么从实际的数据中提取有限的交通信息。在本文中，我们研究如何根据从不同传感器和车辆网络收集到的数据来确定交通信号的持续时间。我们提出了一个深度强化学习模型来控制交通灯。在该模型中，我们通过收集数据并将整个交叉点划分为小网格来将复杂交通场景量化为状态。交通灯的时间变化是作为高维马尔可夫决策过程建模的动作。奖励是两个周期之间的累积等待时间差。为了解决这个模型，卷积神经网络被用来将状态映射到奖励。所提出的模型由若干组件组成以提高性能，例如决斗网络，目标网络，双重Q学习网络以及优先体验重播。我们通过仿真模拟城市可行性（SUMO）在车载网络中评估我们的模型，仿真结果显示了我们的模型在控制交通灯方面的效率。

##### URL
[http://arxiv.org/abs/1803.11115](http://arxiv.org/abs/1803.11115)

##### PDF
[http://arxiv.org/pdf/1803.11115](http://arxiv.org/pdf/1803.11115)

