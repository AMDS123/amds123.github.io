---
layout: post
title: "Recurrent Predictive State Policy Networks"
date: 2018-03-05 03:59:48
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction Gradient_Descent
author: Ahmed Hefny, Zita Marinho, Wen Sun, Siddhartha Srinivasa, Geoffrey Gordon
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Recurrent Predictive State Policy (RPSP) networks, a recurrent architecture that brings insights from predictive state representations to reinforcement learning in partially observable environments. Predictive state policy networks consist of a recursive filter, which keeps track of a belief about the state of the environment, and a reactive policy that directly maps beliefs to actions, to maximize the cumulative reward. The recursive filter leverages predictive state representations (PSRs) (Rosencrantz and Gordon, 2004; Sun et al., 2016) by modeling predictive state-- a prediction of the distribution of future observations conditioned on history and future actions. This representation gives rise to a rich class of statistically consistent algorithms (Hefny et al., 2018) to initialize the recursive filter. Predictive state serves as an equivalent representation of a belief state. Therefore, the policy component of the RPSP-network can be purely reactive, simplifying training while still allowing optimal behaviour. Moreover, we use the PSR interpretation during training as well, by incorporating prediction error in the loss function. The entire network (recursive filter and reactive policy) is still differentiable and can be trained using gradient based methods. We optimize our policy using a combination of policy gradient based on rewards (Williams, 1992) and gradient descent based on prediction error. We show the efficacy of RPSP-networks under partial observability on a set of robotic control tasks from OpenAI Gym. We empirically show that RPSP-networks perform well compared with memory-preserving networks such as GRUs, as well as finite memory models, being the overall best performing method.

##### Abstract (translated by Google)
我们介绍了经常性预测状态策略（RPSP）网络，这是一种经常性的架构，可以从预测状态表示中获得洞察力，并在部分可观察的环境中强化学习。预测状态策略网络由一个递归过滤器组成，该过滤器记录对环境状态的信念，以及一个将信念直接映射到行为的被动策略，以最大化累积奖励。递归滤波器利用预测状态表示（PSR）（Rosencrantz和Gordon，2004; Sun等，2016），通过建模预测状态 - 预测未来观察分布对历史和未来行为的条件。这种表示产生了丰富的统计一致性算法（Hefny等，2018）来初始化递归滤波器。预测状态用作信念状态的等价表示。因此，RPSP网络的政策组成部分可能是纯粹的反应，简化了培训，同时仍然允许最佳行为。此外，我们在训练期间也使用PSR解释，将预测误差纳入损失函数中。整个网络（递归滤波器和反应策略）仍然可以区分，并且可以使用基于渐变的方法进行训练。我们使用基于奖励的政策梯度（Williams，1992）和基于预测误差的梯度下降的组合来优化我们的政策。我们展示了RPSP网络在部分可观测性下对来自OpenAI Gym的一组机器人控制任务的有效性。我们凭经验证明，RPSP网络与GRU等内存保留网络以及有限内存模型相比表现良好，这是整体性能最佳的方法。

##### URL
[http://arxiv.org/abs/1803.01489](http://arxiv.org/abs/1803.01489)

##### PDF
[http://arxiv.org/pdf/1803.01489](http://arxiv.org/pdf/1803.01489)

