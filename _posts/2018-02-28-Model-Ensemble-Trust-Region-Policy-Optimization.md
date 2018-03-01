---
layout: post
title: "Model-Ensemble Trust-Region Policy Optimization"
date: 2018-02-28 18:58:22
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Deep_Learning
author: Thanard Kurutach, Ignasi Clavera, Yan Duan, Aviv Tamar, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free reinforcement learning (RL) methods are succeeding in a growing number of tasks, aided by recent advances in deep learning. However, they tend to suffer from high sample complexity, which hinders their use in real-world domains. Alternatively, model-based reinforcement learning promises to reduce sample complexity, but tends to require careful tuning and to date have succeeded mainly in restrictive domains where simple models are sufficient for learning. In this paper, we analyze the behavior of vanilla model-based reinforcement learning methods when deep neural networks are used to learn both the model and the policy, and show that the learned policy tends to exploit regions where insufficient data is available for the model to be learned, causing instability in training. To overcome this issue, we propose to use an ensemble of models to maintain the model uncertainty and regularize the learning process. We further show that the use of likelihood ratio derivatives yields much more stable learning than backpropagation through time. Altogether, our approach Model-Ensemble Trust-Region Policy Optimization (ME-TRPO) significantly reduces the sample complexity compared to model-free deep RL methods on challenging continuous control benchmark tasks.

##### Abstract (translated by Google)
在最近的深度学习进展的辅助下，免模型强化学习（RL）方法在越来越多的任务中取得成功。然而，他们倾向于高样本复杂性，这阻碍了他们在现实世界中的使用。另外，基于模型的强化学习有望减少样本的复杂性，但往往需要仔细调整，并且迄今为止主要在限制性域中成功，其中简单模型足以用于学习。在本文中，我们分析了当使用深度神经网络来学习模型和策略时，基于vanilla模型的强化学习方法的行为，并且表明学习策略倾向于利用模型中没有足够数据可用的区域来学会，造成训练不稳定。为了克服这个问题，我们建议使用模型集合来保持模型的不确定性并规范学习过程。我们进一步表明，使用似然比导数产生比反向传播时间更稳定的学习。总而言之，我们的方法模型 - 集成信任 - 区域策略优化（ME-TRPO）与具有挑战性的连续控制基准任务的无模型深RL方法相比，显着降低了样本复杂性。

##### URL
[http://arxiv.org/abs/1802.10592](http://arxiv.org/abs/1802.10592)

##### PDF
[http://arxiv.org/pdf/1802.10592](http://arxiv.org/pdf/1802.10592)

