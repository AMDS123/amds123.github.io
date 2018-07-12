---
layout: post
title: "Algorithmic Framework for Model-based Reinforcement Learning with Theoretical Guarantees"
date: 2018-07-10 20:53:04
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Prediction
author: Huazhe Xu, Yuanzhi Li, Yuandong Tian, Trevor Darrell, Tengyu Ma
mathjax: true
---

* content
{:toc}

##### Abstract
While model-based reinforcement learning has empirically been shown to significantly reduce the sample complexity that hinders model-free RL, the theoretical understanding of such methods has been rather limited. In this paper, we introduce a novel algorithmic framework for designing and analyzing model-based RL algorithms with theoretical guarantees, and a practical algorithm Optimistic Lower Bounds Optimization (OLBO). In particular, we derive a theoretical guarantee of monotone improvement for model-based RL with our framework. We iteratively build a lower bound of the expected reward based on the estimated dynamical model and sample trajectories, and maximize it jointly over the policy and the model. Assuming the optimization in each iteration succeeds, the expected reward is guaranteed to improve. The framework also incorporates an optimism-driven perspective, and reveals the intrinsic measure for the model prediction error. Preliminary simulations demonstrate that our approach outperforms the standard baselines on continuous control benchmark tasks.

##### Abstract (translated by Google)
虽然基于模型的强化学习已经证明可以显着降低阻碍无模型RL的样本复杂性，但对这些方法的理论理解相当有限。在本文中，我们介绍了一种新的算法框架，用于设计和分析基于模型的RL算法的理论保证，以及一个实用的算法乐观下界优化（OLBO）。特别是，我们用我们的框架得出了基于模型的RL单调改进的理论保证。我们基于估计的动态模型和样本轨迹迭代地建立预期奖励的下限，并在策略和模型上共同最大化它。假设每次迭代中的优化成功，则保证预期的奖励得到改善。该框架还结合了乐观驱动的观点，并揭示了模型预测误差的内在度量。初步模拟表明，我们的方法在连续控制基准测试任务上优于标准基线。

##### URL
[http://arxiv.org/abs/1807.03858](http://arxiv.org/abs/1807.03858)

##### PDF
[http://arxiv.org/pdf/1807.03858](http://arxiv.org/pdf/1807.03858)

