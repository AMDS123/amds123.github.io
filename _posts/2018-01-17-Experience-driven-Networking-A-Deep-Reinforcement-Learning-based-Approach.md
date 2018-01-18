---
layout: post
title: "Experience-driven Networking: A Deep Reinforcement Learning based Approach"
date: 2018-01-17 17:09:01
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Zhiyuan Xu, Jian Tang, Jingsong Meng, Weiyi Zhang, Yanzhi Wang, Chi Harold Liu, Dejun Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Modern communication networks have become very complicated and highly dynamic, which makes them hard to model, predict and control. In this paper, we develop a novel experience-driven approach that can learn to well control a communication network from its own experience rather than an accurate mathematical model, just as a human learns a new skill (such as driving, swimming, etc). Specifically, we, for the first time, propose to leverage emerging Deep Reinforcement Learning (DRL) for enabling model-free control in communication networks; and present a novel and highly effective DRL-based control framework, DRL-TE, for a fundamental networking problem: Traffic Engineering (TE). The proposed framework maximizes a widely-used utility function by jointly learning network environment and its dynamics, and making decisions under the guidance of powerful Deep Neural Networks (DNNs). We propose two new techniques, TE-aware exploration and actor-critic-based prioritized experience replay, to optimize the general DRL framework particularly for TE. To validate and evaluate the proposed framework, we implemented it in ns-3, and tested it comprehensively with both representative and randomly generated network topologies. Extensive packet-level simulation results show that 1) compared to several widely-used baseline methods, DRL-TE significantly reduces end-to-end delay and consistently improves the network utility, while offering better or comparable throughput; 2) DRL-TE is robust to network changes; and 3) DRL-TE consistently outperforms a state-ofthe-art DRL method (for continuous control), Deep Deterministic Policy Gradient (DDPG), which, however, does not offer satisfying performance.

##### Abstract (translated by Google)
现代通信网络变得非常复杂和高度动态化，这使得它们难以建模，预测和控制。在本文中，我们开发了一种新颖的体验驱动方法，就像人类学习新技能（如驾驶，游泳等）一样，学习如何从自己的经验中更好地控制通信网络，而不是准确的数学模型。具体而言，我们首次提出利用新兴的深度增强学习（DRL）来实现通信网络中的无模型控制;并提出了一个基于DRL的新型高效控制框架DRL-TE，用于一个基本的网络问题：流量工程（TE）。所提出的框架通过联合学习网络环境及其动力学，并在强大的深度神经网络（DNNs）的指导下做出决策，来最大化广泛使用的效用函数。我们提出了两种新的技术，TE意识探索和基于演员批评的优先体验重播，以优化TE的一般DRL框架。为了验证和评估所提出的框架，我们在ns-3中实现了它，并且使用代表性的和随机生成的网络拓扑进行了全面的测试。广泛的数据包级仿真结果表明：1）与几种广泛使用的基线方法相比，DRL-TE显着降低了端到端的延迟并持续改善了网络效用，同时提供了更好的或可比较的吞吐量; 2）DRL-TE对于网络变化是强大的;和3）DRL-TE始终优于最先进的DRL方法（用于连续控制），深度确定性策略梯度（DDPG），但是它不能提供令人满意的性能。

##### URL
[http://arxiv.org/abs/1801.05757](http://arxiv.org/abs/1801.05757)

##### PDF
[http://arxiv.org/pdf/1801.05757](http://arxiv.org/pdf/1801.05757)

