---
layout: post
title: "Deep Learning with Experience Ranking Convolutional Neural Network for Robot Manipulator"
date: 2018-09-16 05:58:46
categories: arXiv_RO
tags: arXiv_RO Sparse Knowledge Face Reinforcement_Learning CNN Deep_Learning Detection Recognition
author: Hai Nguyen, Hung Manh La, Matthew Deans
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning, more specifically Convolutional Neural Networks (CNN), has surpassed human ability in some visual recognition tasks such as detection of traffic signs, faces and handwritten numbers. On the other hand, even state-of-the-art reinforcement learning (RL) methods have difficulties in environments with sparse and binary rewards. They requires manually shaping reward functions, which might be challenging to come up with. These tasks, however, are trivial to human. One of the reasons that human are better learners in these tasks is that we are embedded with much prior knowledge of the world. These knowledge might be either embedded in our genes or learned from imitation - a type of supervised learning. For that reason, the best way to narrow the gap between machine and human learning ability should be to mimic how we learn so well in various tasks by a combination of RL and supervised learning. Our method, which integrates Deep Deterministic Policy Gradients and Hindsight Experience Replay (RL method specifically dealing with sparse rewards) with an experience ranking CNN, provides a significant speedup over the learning curve on simulated robotics tasks. Experience ranking allows high-reward transitions to be replayed more frequently, and therefore help learn more efficiently. Our proposed approach can also speed up learning in any other tasks that provide additional information for experience ranking.

##### Abstract (translated by Google)
监督学习，更具体地说是卷积神经网络（CNN），在某些视觉识别任务中超越了人类的能力，例如检测交通标志，面部和手写数字。另一方面，即使是最先进的强化学习（RL）方法在具有稀疏和二元奖励的环境中也存在困难。他们需要手动塑造奖励功能，这可能具有挑战性。然而，这些任务对人类来说是微不足道的。在这些任务中，人类是更好的学习者的原因之一是我们已经掌握了许多关于世界的先验知识。这些知识可以嵌入我们的基因中，也可以从模仿中学习 - 一种监督学习。因此，缩小机器与人类学习能力之间差距的最佳方法应该是模仿我们如何通过RL和监督学习的结合在各种任务中如此好地学习。我们的方法集成了深度确定性策略梯度和后见之明体验重放（专门处理稀疏奖励的RL方法）和CNN经验排名，为模拟机器人任务的学习曲线提供了显着的加速。体验排名允许更频繁地重放高回报过渡，因此有助于更有效地学习。我们提出的方法还可以加快学习任何其他任务，为经验排名提供额外信息。

##### URL
[http://arxiv.org/abs/1809.05819](http://arxiv.org/abs/1809.05819)

##### PDF
[http://arxiv.org/pdf/1809.05819](http://arxiv.org/pdf/1809.05819)

