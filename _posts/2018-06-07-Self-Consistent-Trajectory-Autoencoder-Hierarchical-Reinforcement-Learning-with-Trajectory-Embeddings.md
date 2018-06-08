---
layout: post
title: "Self-Consistent Trajectory Autoencoder: Hierarchical Reinforcement Learning with Trajectory Embeddings"
date: 2018-06-07 17:49:08
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Embedding Represenation_Learning Prediction
author: John D. Co-Reyes, YuXuan Liu, Abhishek Gupta, Benjamin Eysenbach, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we take a representation learning perspective on hierarchical reinforcement learning, where the problem of learning lower layers in a hierarchy is transformed into the problem of learning trajectory-level generative models. We show that we can learn continuous latent representations of trajectories, which are effective in solving temporally extended and multi-stage problems. Our proposed model, SeCTAR, draws inspiration from variational autoencoders, and learns latent representations of trajectories. A key component of this method is to learn both a latent-conditioned policy and a latent-conditioned model which are consistent with each other. Given the same latent, the policy generates a trajectory which should match the trajectory predicted by the model. This model provides a built-in prediction mechanism, by predicting the outcome of closed loop policy behavior. We propose a novel algorithm for performing hierarchical RL with this model, combining model-based planning in the learned latent space with an unsupervised exploration objective. We show that our model is effective at reasoning over long horizons with sparse rewards for several simulated tasks, outperforming standard reinforcement learning methods and prior methods for hierarchical reasoning, model-based planning, and exploration.

##### Abstract (translated by Google)
在这项工作中，我们采用了表示层次强化学习的学习视角，其中层次结构中的下层学习问题转化为学习轨迹级生成模型的问题。我们表明，我们可以学习轨迹的连续潜在表示，这对解决时间延长和多阶段问题是有效的。我们提出的模型SeCTAR从变分自编码器中获得灵感，并学习轨迹的潜在表示。这种方法的一个关键组成部分是学习相互一致的潜规则和潜规则模型。在相同的潜在情况下，政策会生成一条轨迹，该轨迹应与模型预测的轨迹相匹配。通过预测闭环策略行为的结果，该模型提供了内置的预测机制。我们提出了一种新的算法，用这种模型执行分层RL，将学习的潜在空间中的基于模型的规划与无监督的勘探目标相结合。我们表明，我们的模型在多个模拟任务的稀疏奖励的长期推理上是有效的，超越了标准的强化学习方法和先前的等级推理方法，基于模型的计划和探索。

##### URL
[http://arxiv.org/abs/1806.02813](http://arxiv.org/abs/1806.02813)

##### PDF
[http://arxiv.org/pdf/1806.02813](http://arxiv.org/pdf/1806.02813)

