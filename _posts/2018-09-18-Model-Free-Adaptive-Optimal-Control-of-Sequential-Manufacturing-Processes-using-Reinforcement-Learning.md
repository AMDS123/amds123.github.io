---
layout: post
title: "Model-Free Adaptive Optimal Control of Sequential Manufacturing Processes using Reinforcement Learning"
date: 2018-09-18 11:20:27
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Johannes Dornheim, Norbert Link, Peter Gumbsch
mathjax: true
---

* content
{:toc}

##### Abstract
A self-learning optimal control algorithm for sequential manufacturing processes with time-discrete control actions is proposed and evaluated with simulated deep drawing processes. The necessary control model is built during consecutive process executions under optimal control via Reinforcement Learning, using the measured product quality as reward after each process execution. Prior model formation, which is required by state-of-the-art algorithms like Model Predictive Control and Approximate Dynamic Programming, is therefore obsolete. This avoids the difficulties in system identification and accurate modelling, which arise with processes subject to non-linear dynamics and stochastic influences. Also runtime complexity problems of these approaches are avoided, which arise when more complex models and larger control prediction horizons are employed. Instead of using pre-created process- and observation-models, Reinforcement Learning algorithms build functions of expected future reward during processing, which are then used for optimal process control decisions. The learning of such expectation functions is realized online by interacting with the process. The proposed algorithm also takes stochastic variations of the process conditions into consideration and is able to cope with partial observability. A method for the adaptive optimal control of partially observable fixed-horizon manufacturing processes, based on Q-learning is developed and studied. The resulting algorithm is instantiated and then evaluated by application to a time-stochastic optimal control problem in metal sheet deep drawing, where the experiments use FEM-simulated processes. The Reinforcement Learning based control shows superior results over the model-based Model Predictive Control and Approximate Dynamic Programming approaches.

##### Abstract (translated by Google)
提出了一种具有时间离散控制动作的顺序制造过程的自学习最优控制算法，并通过模拟深拉过程进行评估。必要的控制模型是在连续过程执行期间通过强化学习在最佳控制下建立的，在每次过程执行后使用测量的产品质量作为奖励。因此，模型预测控制和近似动态规划等最先进算法所需的先前模型形成已经过时。这避免了系统识别和精确建模的困难，这些困难是由于受到非线性动力学和随机影响的过程而产生的。还避免了这些方法的运行时复杂性问题，这些问题在采用更复杂的模型和更大的控制预测范围时出现。增强学习算法不是使用预先创建的过程和观察模型，而是在处理过程中构建预期未来奖励的功能，然后用于最佳过程控制决策。通过与过程交互来在线实现对这种期望功能的学习。所提出的算法还考虑了过程条件的随机变化，并且能够应对部分可观察性。开发并研究了一种基于Q学习的部分可观测固定水平制造过程的自适应最优控制方法。生成的算法被实例化，然后通过应用于金属板深拉伸中的时间随机最优控制问题进行评估，其中实验使用FEM模拟过程。基于模型的模型预测控制和近似动态规划方法，基于强化学习的控制显示出优越的结果。

##### URL
[https://arxiv.org/abs/1809.06646](https://arxiv.org/abs/1809.06646)

##### PDF
[https://arxiv.org/pdf/1809.06646](https://arxiv.org/pdf/1809.06646)

