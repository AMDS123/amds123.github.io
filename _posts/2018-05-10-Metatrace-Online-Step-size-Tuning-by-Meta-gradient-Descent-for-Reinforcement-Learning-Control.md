---
layout: post
title: "Metatrace: Online Step-size Tuning by Meta-gradient Descent for Reinforcement Learning Control"
date: 2018-05-10 20:00:50
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Gradient_Descent
author: Kenny Young, Baoxiang Wang, Matthew E. Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) has had many successes in both "deep" and "shallow" settings. In both cases, significant hyperparameter tuning is often required to achieve good performance. Furthermore, when nonlinear function approximation is used, non-stationarity in the state representation can lead to learning instability. A variety of techniques exist to combat this --- most notably large experience replay buffers or the use of multiple parallel actors. These techniques come at the cost of moving away from the online RL problem as it is traditionally formulated (i.e., a single agent learning online without maintaining a large database of training examples). Meta-learning can potentially help with both these issues by tuning hyperparameters online and allowing the algorithm to more robustly adjust to non-stationarity in a problem. This paper applies meta-gradient descent to derive a set of step-size tuning algorithms specifically for online RL control with eligibility traces. Our novel technique, Metatrace, makes use of an eligibility trace analogous to methods like $TD(\lambda)$. We explore tuning both a single scalar step-size and a separate step-size for each learned parameter. We evaluate Metatrace first for control with linear function approximation in the classic mountain car problem and then in a noisy, non-stationary version. Finally, we apply Metatrace for control with nonlinear function approximation in 5 games in the Arcade Learning Environment where we explore how it impacts learning speed and robustness to initial step-size choice. Results show that the meta-step-size parameter of Metatrace is easy to set, Metatrace can speed learning, and Metatrace can allow an RL algorithm to deal with non-stationarity in the learning task.

##### Abstract (translated by Google)
强化学习（RL）在“深度”和“浅度”环境中取得了许多成功。在这两种情况下，通常都需要进行重要的超参数调整才能获得良好的性能。此外，当使用非线性函数逼近时，状态表示中的非平稳性会导致学习不稳定。存在多种技术来对抗这种情况---最显着的是大型体验重放缓冲区或使用多个并行参与者。这些技术的代价是远离在线RL问题，因为它是传统上制定的（即，单个代理在线学习而没有维护大型训练实例数据库）。元学习可以通过在线调整超参数并允许算法更强大地适应问题中的非平稳性，从而有助于解决这两个问题。本文应用元梯度下降法来推导出一组专门用于在线RL控制的步长调整算法，并具有资格痕迹。我们的新技术Metatrace使用类似于$ TD（\ lambda）$等方法的资格追踪。我们探索调整每个学习参数的单个标量步长和单独的步长。我们首先评估Metatrace在经典山地车问题中的线性函数逼近控制，然后在嘈杂的非平稳版本中进行控制。最后，我们在街机学习环境的5场游戏中将Metatrace应用于非线性函数逼近的控制，我们将探索它如何影响学习速度和初始步长选择的稳健性。结果表明，Metatrace的元步长参数容易设置，Metatrace可以加速学习，而Metatrace可以允许RL算法处理学习任务中的非平稳性问题。

##### URL
[https://arxiv.org/abs/1805.04514](https://arxiv.org/abs/1805.04514)

##### PDF
[https://arxiv.org/pdf/1805.04514](https://arxiv.org/pdf/1805.04514)

