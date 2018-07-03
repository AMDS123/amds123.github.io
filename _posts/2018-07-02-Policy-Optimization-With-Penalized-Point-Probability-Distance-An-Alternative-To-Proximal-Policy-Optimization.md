---
layout: post
title: "Policy Optimization With Penalized Point Probability Distance: An Alternative To Proximal Policy Optimization"
date: 2018-07-02 02:49:36
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Xiangxiang Chu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a first order gradient reinforcement learning algorithm, which can be seen as a variant for Trust Region Policy Optimization(TRPO). This method, which we call policy optimization with penalized point probability distance (POP3D), keeps almost all positive spheres of proximal policy optimization (PPO) such as easy implementation, fast learning and high score capability. As PPO, we also use a single surrogate objective without constraints, where a penalized item based on point probability distance is included to prevent update step from growing too large. Experiments verify that POP3D is state-of-the-art within 40 million frame steps on 49 Atari games based on two common metrics, which can be a competitive alternative to PPO. Moreover, comparison experiments regarding PPO based on Mujoco environment verify that POP3D is also competitive in continuous domain. In addition, we release the code on github https://github.com/cxxgtxy/POP3D.git.

##### Abstract (translated by Google)
本文提出了一阶梯度强化学习算法，可以看作是信任区域政策优化（TRPO）的变种。这种方法，我们称之为惩罚点概率距离（POP3D）的政策优化，几乎保留了近端政策优化（PPO）的所有正面领域，如易于实施，快速学习和高分能力。作为PPO，我们还使用没有约束的单个替代目标，其中包括基于点概率距离的惩罚项目以防止更新步骤变得太大。实验证明POP3D在49个Atari游戏中基于两个常见指标在4000万帧步骤中是最先进的，这可以是PPO的竞争替代品。此外，基于Mujoco环境的PPO对比实验验证了POP3D在连续域中也具有竞争力。另外，我们在github上发布代码https://github.com/cxxgtxy/POP3D.git。

##### URL
[http://arxiv.org/abs/1807.00442](http://arxiv.org/abs/1807.00442)

##### PDF
[http://arxiv.org/pdf/1807.00442](http://arxiv.org/pdf/1807.00442)

