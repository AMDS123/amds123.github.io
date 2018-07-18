---
layout: post
title: "Shielded Decision-Making in MDPs"
date: 2018-07-16 20:29:04
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Nils Jansen, Bettina K&#xf6;nighofer, Sebastian Junges, Roderick Bloem
mathjax: true
---

* content
{:toc}

##### Abstract
A prominent problem in artificial intelligence and machine learning is the safe exploration of an environment. In particular, reinforcement learning is a well-known technique to determine optimal policies for complicated dynamic systems, but suffers from the fact that such policies may induce harmful behavior. We present the concept of a shield that forces decision-making to provably adhere to safety requirements with high probability. Our method exploits the inherent uncertainties in scenarios given by Markov decision processes. We present a method to compute probabilities of decision making regarding temporal logic constraints. We use that information to realize a shield that---when applied to a reinforcement learning algorithm---ensures (near-)optimal behavior both for the safety constraints and for the actual learning objective. In our experiments, we show on the arcade game PAC-MAN that the learning efficiency increases as the learning needs orders of magnitude fewer episodes. We show tradeoffs between sufficient progress in exploration of the environment and ensuring strict safety.

##### Abstract (translated by Google)
人工智能和机器学习中的一个突出问题是对环境的安全探索。特别地，强化学习是用于确定复杂动态系统的最优策略的众所周知的技术，但是受到这样的策略可能引起有害行为的事实的影响。我们提出了一种盾牌的概念，迫使决策以极高的概率证明其符合安全要求。我们的方法利用马尔可夫决策过程给出的情景中的固有不确定性。我们提出了一种计算时间逻辑约束决策概率的方法。我们使用该信息来实现一种屏蔽 - 当应用于强化学习算法时 - 确保（近似）安全约束和实际学习目标的最佳行为。在我们的实验中，我们在街机游戏PAC-MAN上显示，学习效率随着学习需要数量级减少而增加。我们展示了在探索环境方面取得足够进展与确保严格安全之间的权衡。

##### URL
[http://arxiv.org/abs/1807.06096](http://arxiv.org/abs/1807.06096)

##### PDF
[http://arxiv.org/pdf/1807.06096](http://arxiv.org/pdf/1807.06096)

