---
layout: post
title: "Smoothed Action Value Functions for Learning Gaussian Policies"
date: 2018-03-06 04:58:20
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Relation
author: Ofir Nachum, Mohammad Norouzi, George Tucker, Dale Schuurmans
mathjax: true
---

* content
{:toc}

##### Abstract
State-action value functions (i.e., Q-values) are ubiquitous in reinforcement learning (RL), giving rise to popular algorithms such as SARSA and Q-learning. We propose a new notion of action value defined by a Gaussian smoothed version of the expected Q-value. We show that such smoothed Q-values still satisfy a Bellman equation, making them learnable from experience sampled from an environment. Moreover, the gradients of expected reward with respect to the mean and covariance of a parameterized Gaussian policy can be recovered from the gradient and Hessian of the smoothed Q-value function. Based on these relationships, we develop new algorithms for training a Gaussian policy directly from a learned smoothed Q-value approximator. The approach is additionally amenable to proximal optimization by augmenting the objective with a penalty on KL-divergence from a previous policy. We find that the ability to learn both a mean and covariance during training leads to significantly improved results on standard continuous control benchmarks.

##### Abstract (translated by Google)
状态动作值函数（即Q值）在强化学习（RL）中无处不在，引起了流行的算法，如SARSA和Q-learning。我们提出了一个由预期Q值的高斯平滑版本定义的动作值的新概念。我们证明这种平滑的Q值仍然满足Bellman方程，使它们可以从环境采样的经验中学习。此外，关于参数化高斯策略的均值和协方差的期望奖励的梯度可以从平滑Q值函数的梯度和Hessian中恢复。基于这些关系，我们开发了新的算法，用于直接从学习的平滑Q值逼近器中训练高斯策略。该方法还适用于通过增加目标而对近端优化进行优化，并对先前策略的KL分歧进行惩罚。我们发现在培训期间学习均值和协方差的能力导致标准连续控制基准的显着改进结果。

##### URL
[http://arxiv.org/abs/1803.02348](http://arxiv.org/abs/1803.02348)

##### PDF
[http://arxiv.org/pdf/1803.02348](http://arxiv.org/pdf/1803.02348)

