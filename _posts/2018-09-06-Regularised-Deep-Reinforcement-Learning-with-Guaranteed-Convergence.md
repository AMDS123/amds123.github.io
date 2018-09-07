---
layout: post
title: "Regularised Deep Reinforcement Learning with Guaranteed Convergence"
date: 2018-09-06 09:27:21
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning CNN
author: Felix Leibfried, Rasul Tutunov, Jordi Grau-Moya, Haitham Bou-Ammar
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Q-networks (DQNs) suffer from two important challenges hindering their application in real-world scenarios. First, DQNs overestimate Q-values which leads to increased sample complexity, and second, no theoretical convergence guarantees have been established. In this paper, we address both problems by introducing an intrinsic penalty signal arising from a Kullback-Leibler (KL) constraint that encourages reduced Q-value estimates. We then prove, for the first time, convergence to a stationary point under a specific scheduling of the penalisation magnitude. Our proofs operate in the deep reinforcement learning setting that considers convolutional and dense layers for Q-function approximation. Furthermore, we prove divergence of standard DQNs using a counter example that relates to the non-optimal choice of the history-scheduling parameter adopted by `vanilla' DQNs. We believe this can shed the light on some of the difficulties reported by researchers and practitioners in the field.

##### Abstract (translated by Google)
深度Q网络（DQN）面临着阻碍其在实际场景中应用的两个重要挑战。首先，DQN高估了Q值，导致样本复杂性增加，其次，没有建立理论上的收敛保证。在本文中，我们通过引入由Kullback-Leibler（KL）约束引起的内在惩罚信号来解决这两个问题，该约束鼓励降低Q值估计。然后，我们首次证明在惩罚量级的特定调度下收敛到静止点。我们的证明在深度强化学习设置中运行，该设置考虑用于Q函数近似的卷积和密集层。此外，我们使用与“vanilla”DQN采用的历史调度参数的非最佳选择相关的计数器示例来证明标准DQN的分歧。我们相信这可以揭示该领域研究人员和从业人员报告的一些困难。

##### URL
[http://arxiv.org/abs/1708.01867](http://arxiv.org/abs/1708.01867)

##### PDF
[http://arxiv.org/pdf/1708.01867](http://arxiv.org/pdf/1708.01867)

