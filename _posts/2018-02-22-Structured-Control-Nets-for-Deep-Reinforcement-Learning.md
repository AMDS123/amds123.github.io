---
layout: post
title: "Structured Control Nets for Deep Reinforcement Learning"
date: 2018-02-22 21:31:34
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Mario Srouji, Jian Zhang, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, Deep Reinforcement Learning has made impressive advances in solving several important benchmark problems for sequential decision making. Many control applications use a generic multilayer perceptron (MLP) for non-vision parts of the policy network. In this work, we propose a new neural network architecture for the policy network representation that is simple yet effective. The proposed Structured Control Net (SCN) splits the generic MLP into two separate sub-modules: a nonlinear control module and a linear control module. Intuitively, the nonlinear control is for forward-looking and global control, while the linear control stabilizes the local dynamics around the residual of global control. We hypothesize that this will bring together the benefits of both linear and nonlinear policies: improve training sample efficiency, final episodic reward, and generalization of learned policy, while requiring a smaller network and being generally applicable to different training methods. We validated our hypothesis with competitive results on simulations from OpenAI MuJoCo, Roboschool, Atari, and a custom 2D urban driving environment, with various ablation and generalization tests, trained with multiple black-box and policy gradient training methods. The proposed architecture has the potential to improve upon broader control tasks by incorporating problem specific priors into the architecture. As a case study, we demonstrate much improved performance for locomotion tasks by emulating the biological central pattern generators (CPGs) as the nonlinear part of the architecture.

##### Abstract (translated by Google)
近年来，Deep Reinforcement Learning在解决几个连续决策的重要基准问题方面取得了令人瞩目的进展。许多控制应用程序对策略网络的非视觉部分使用通用多层感知器（MLP）。在这项工作中，我们提出了一个简单而有效的策略网络表示的新神经网络体系结构。所提出的结构化控制网（SCN）将通用MLP分成两个独立的子模块：非线性控制模块和线性控制模块。直观地说，非线性控制用于前瞻性和全局控制，而线性控制稳定全局控制残差周围的局部动态。我们假设这将把线性和非线性策略的好处结合在一起：提高训练样本效率，最终情节奖励以及学习策略的一般化，同时要求较小的网络并且通常适用于不同的训练方法。我们通过OpenAI MuJoCo，Roboschool，Atari以及定制的2D城市驾驶环境的仿真验证了我们的假设，其中包含各种消融和泛化测试，并使用多种黑盒和策略梯度训练方法进行训练。所提出的架构有可能通过将特定于问题的先验并入架构来改进更广泛的控制任务。作为一个案例研究，我们通过模拟生物中心模式生成器（CPG）作为体系结构的非线性部分，证明了运动任务的性能大大提高。

##### URL
[https://arxiv.org/abs/1802.08311](https://arxiv.org/abs/1802.08311)

##### PDF
[https://arxiv.org/pdf/1802.08311](https://arxiv.org/pdf/1802.08311)

