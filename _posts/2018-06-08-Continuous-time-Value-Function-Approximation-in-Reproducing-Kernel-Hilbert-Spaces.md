---
layout: post
title: "Continuous-time Value Function Approximation in Reproducing Kernel Hilbert Spaces"
date: 2018-06-08 06:50:14
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Motoya Ohnishi, Masahiro Yukawa, Mikael Johansson, Masashi Sugiyama
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by the success of reinforcement learning (RL) for discrete-time tasks such as AlphaGo and Atari games, there has been a recent surge of interest in using RL for continuous-time control of physical systems (cf. many challenging tasks in OpenAI Gym and the DeepMind Control Suite). Since discretization of time is susceptible to error, it is methodologically more desirable to handle the system dynamics directly in continuous time. However, very few techniques exist for continuous-time RL and they lack flexibility in value function approximation. In this paper, we propose a novel framework for continuous-time value function approximation based on reproducing kernel Hilbert spaces. The resulting framework is so flexible that it can accommodate any kind of kernel-based approach, such as Gaussian processes and the adaptive projected subgradient method, and it allows us to handle uncertainties and nonstationarity without prior knowledge about the environment or what basis functions to employ. We demonstrate the validity of the presented framework through experiments.

##### Abstract (translated by Google)
在AlphaGo和Atari游戏等离散时间任务的强化学习（RL）的成功推动下，最近人们对使用RL进行连续时间物理系统控制感兴趣不断（参见OpenAI Gym中的许多具有挑战性的任务和DeepMind控制套件）。由于时间离散容易出错，因此在方法上更希望直接在连续时间内处理系统动态。然而，对于连续时间RL，很少有技术存在，并且它们在值函数近似方面缺乏灵活性。在本文中，我们提出了一种基于再生核Hilbert空间的连续时间值函数逼近的新框架。由此产生的框架非常灵活，可以适应任何种类的基于内核的方法，如高斯过程和自适应投影次梯度方法，并且它允许我们处理不确定性和非平稳性，而无需事先了解环境或使用何种基本功能。我们通过实验证明了所提出框架的有效性。

##### URL
[http://arxiv.org/abs/1806.02985](http://arxiv.org/abs/1806.02985)

##### PDF
[http://arxiv.org/pdf/1806.02985](http://arxiv.org/pdf/1806.02985)

