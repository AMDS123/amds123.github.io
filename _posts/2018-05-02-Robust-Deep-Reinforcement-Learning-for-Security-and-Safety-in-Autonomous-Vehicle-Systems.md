---
layout: post
title: "Robust Deep Reinforcement Learning for Security and Safety in Autonomous Vehicle Systems"
date: 2018-05-02 19:03:37
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning RNN
author: Aidin Ferdowsi, Ursula Challita, Walid Saad, Narayan B. Mandayam
mathjax: true
---

* content
{:toc}

##### Abstract
To operate effectively in tomorrow's smart cities, autonomous vehicles (AVs) must rely on intra-vehicle sensors such as camera and radar as well as inter-vehicle communication. Such dependence on sensors and communication links exposes AVs to cyber-physical (CP) attacks by adversaries that seek to take control of the AVs by manipulating their data. Thus, to ensure safe and optimal AV dynamics control, the data processing functions at AVs must be robust to such CP attacks. To this end, in this paper, the state estimation process for monitoring AV dynamics, in presence of CP attacks, is analyzed and a novel adversarial deep reinforcement learning (RL) algorithm is proposed to maximize the robustness of AV dynamics control to CP attacks. The attacker's action and the AV's reaction to CP attacks are studied in a game-theoretic framework. In the formulated game, the attacker seeks to inject faulty data to AV sensor readings so as to manipulate the inter-vehicle optimal safe spacing and potentially increase the risk of AV accidents or reduce the vehicle flow on the roads. Meanwhile, the AV, acting as a defender, seeks to minimize the deviations of spacing so as to ensure robustness to the attacker's actions. Since the AV has no information about the attacker's action and due to the infinite possibilities for data value manipulations, the outcome of the players' past interactions are fed to long-short term memory (LSTM) blocks. Each player's LSTM block learns the expected spacing deviation resulting from its own action and feeds it to its RL algorithm. Then, the the attacker's RL algorithm chooses the action which maximizes the spacing deviation, while the AV's RL algorithm tries to find the optimal action that minimizes such deviation.

##### Abstract (translated by Google)
为了在未来的智能城市有效运作，自主车辆（AV）必须依靠车内传感器（例如摄像头和雷达）以及车辆间通信。这种对传感器和通信链路的依赖使得AV受到攻击者的网络物理（CP）攻击，这些攻击者试图通过操纵他们的数据来控制AV。因此，为了确保安全和最佳的AV动态控制，AV中的数据处理功能必须对这种CP攻击具有强大的鲁棒性。为此，本文分析了在存在CP攻击情况下监视AV动态的状态估计过程，并提出了一种新的对抗深度强化学习（RL）算法，以最大化AV动态控制对CP攻击的稳健性。攻击者的行为和AV对CP攻击的反应在博弈论框架中进行了研究。在制定的游戏中，攻击者寻求向AV传感器读数注入错误数据，以操纵车辆间最佳安全间距，并潜在地增加AV事故的风险或减少道路上的车辆流量。同时，AV作为一名防守者，旨在尽量减少间距的偏差，以确保攻击者行动的稳健性。由于AV没有关于攻击者行为的信息，并且由于数据值操作的无限可能性，因此玩家过去交互的结果被输入到长期记忆（LSTM）块中。每个玩家的LSTM模块学习由其自身行为产生的预期间距偏差并将其馈送给其RL算法。然后，攻击者的RL算法选择最大化间距偏差的动作，而AV的RL算法试图找到最小化这种偏差的最佳动作。

##### URL
[http://arxiv.org/abs/1805.00983](http://arxiv.org/abs/1805.00983)

##### PDF
[http://arxiv.org/pdf/1805.00983](http://arxiv.org/pdf/1805.00983)

