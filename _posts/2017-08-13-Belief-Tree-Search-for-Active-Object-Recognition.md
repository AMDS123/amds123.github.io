---
layout: post
title: "Belief Tree Search for Active Object Recognition"
date: 2017-08-13 13:24:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning RNN Recognition
author: Mohsen Malmir, Garrison W. Cottrell
mathjax: true
---

* content
{:toc}

##### Abstract
Active Object Recognition (AOR) has been approached as an unsupervised learning problem, in which optimal trajectories for object inspection are not known and are to be discovered by reducing label uncertainty measures or training with reinforcement learning. Such approaches have no guarantees of the quality of their solution. In this paper, we treat AOR as a Partially Observable Markov Decision Process (POMDP) and find near-optimal policies on training data using Belief Tree Search (BTS) on the corresponding belief Markov Decision Process (MDP). AOR then reduces to the problem of knowledge transfer from near-optimal policies on training set to the test set. We train a Long Short Term Memory (LSTM) network to predict the best next action on the training set rollouts. We sho that the proposed AOR method generalizes well to novel views of familiar objects and also to novel objects. We compare this supervised scheme against guided policy search, and find that the LSTM network reaches higher recognition accuracy compared to the guided policy method. We further look into optimizing the observation function to increase the total collected reward of optimal policy. In AOR, the observation function is known only approximately. We propose a gradient-based method update to this approximate observation function to increase the total reward of any policy. We show that by optimizing the observation function and retraining the supervised LSTM network, the AOR performance on the test set improves significantly.

##### Abstract (translated by Google)
主动对象识别（AOR）已经作为一个无监督的学习问题来处理，其中目标检测的最佳轨迹是未知的，并且通过减少标签不确定性测量或通过强化学习来训练来发现。这种方法无法保证解决方案的质量。在本文中，我们将AOR作为部分可观察马尔可夫决策过程（POMDP），并使用信仰树搜索（Belief Tree Search，BTS）在相应的信念马尔可夫决策过程（MDP）上找到近似最优策略。 AOR然后简化为从训练集的近乎最优策略到测试集的知识转移问题。我们训练一个长期短期记忆（LSTM）网络来预测训练集推广的最佳下一步行动。我们认为，所提出的AOR方法能够很好地概括熟悉的对象的新颖视图，也能够推广到新颖的对象。我们将这个监督方案与引导性策略搜索进行比较，发现LSTM网络比指导性策略方法具有更高的识别准确性。进一步研究优化观察函数，增加最优策略的总收益。在AOR中，观测函数只是近似的。我们提出一个基于梯度的方法更新这个近似的观测函数来增加任何政策的总回报。我们证明，通过优化观测函数和重新训练有监督的LSTM网络，测试集上的AOR性能显着提高。

##### URL
[https://arxiv.org/abs/1708.03901](https://arxiv.org/abs/1708.03901)

##### PDF
[https://arxiv.org/pdf/1708.03901](https://arxiv.org/pdf/1708.03901)

