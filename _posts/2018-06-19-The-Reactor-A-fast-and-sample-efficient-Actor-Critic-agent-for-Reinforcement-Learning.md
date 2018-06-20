---
layout: post
title: "The Reactor: A fast and sample-efficient Actor-Critic agent for Reinforcement Learning"
date: 2018-06-19 15:32:15
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Audrunas Gruslys, Will Dabney, Mohammad Gheshlaghi Azar, Bilal Piot, Marc Bellemare, Remi Munos
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a new agent architecture, called Reactor, which combines multiple algorithmic and architectural contributions to produce an agent with higher sample-efficiency than Prioritized Dueling DQN (Wang et al., 2016) and Categorical DQN (Bellemare et al., 2017), while giving better run-time performance than A3C (Mnih et al., 2016). Our first contribution is a new policy evaluation algorithm called Distributional Retrace, which brings multi-step off-policy updates to the distributional reinforcement learning setting. The same approach can be used to convert several classes of multi-step policy evaluation algorithms designed for expected value evaluation into distributional ones. Next, we introduce the \b{eta}-leave-one-out policy gradient algorithm which improves the trade-off between variance and bias by using action values as a baseline. Our final algorithmic contribution is a new prioritized replay algorithm for sequences, which exploits the temporal locality of neighboring observations for more efficient replay prioritization. Using the Atari 2600 benchmarks, we show that each of these innovations contribute to both the sample efficiency and final agent performance. Finally, we demonstrate that Reactor reaches state-of-the-art performance after 200 million frames and less than a day of training.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种称为Reactor的新代理体系结构，该体系结合了多种算法和体系结构贡献，以产生比Prioritized Dueling DQN（Wang et al。，2016）和Categorical DQN（Bellemare et al。， 2017），同时提供比A3C更好的运行时间性能（Mnih et al。，2016）。我们的第一个贡献是一个名为Distributional Retrace的新策略评估算法，该算法为分布式强化学习环境带来了多步关闭策略更新。可以使用相同的方法将为预期值评估设计的多阶段策略评估算法转换为分布式策略评估算法。接下来，我们介绍通过使用行动值作为基线来改进方差和偏差之间的折衷的\ b -leave-one-out策略梯度算法。我们最后的算法贡献是针对序列的一种新的优先重放算法，它利用相邻观测的时间局部性来实现更有效的重放优先级。使用Atari 2600基准测试，我们发现每一项创新都有助于样品效率和最终代理性能。最后，我们证明反应堆在2亿帧之后达到最新的性能，并且少于一天的训练。

##### URL
[http://arxiv.org/abs/1704.04651](http://arxiv.org/abs/1704.04651)

##### PDF
[http://arxiv.org/pdf/1704.04651](http://arxiv.org/pdf/1704.04651)

