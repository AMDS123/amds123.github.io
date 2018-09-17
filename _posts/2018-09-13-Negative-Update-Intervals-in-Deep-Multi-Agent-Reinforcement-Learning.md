---
layout: post
title: "Negative Update Intervals in Deep Multi-Agent Reinforcement Learning"
date: 2018-09-13 15:46:55
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Gregory Palmer, Karl Tuyls, Rahul Savani
mathjax: true
---

* content
{:toc}

##### Abstract
In Multi-Agent Reinforcement Learning, independent cooperative learners must overcome a number of pathologies in order to learn optimal joint policies. These pathologies include action-shadowing, stochasticity, the moving target and alter-exploration problems (Matignon, Laurent, and Le Fort-Piat 2012; Wei and Luke 2016). Numerous methods have been proposed to address these pathologies, but evaluations are predominately conducted in repeated strategic-form games and stochastic games consisting of only a small number of state transitions. This raises the question of the scalability of the methods to complex, temporally extended, partially observable domains with stochastic transitions and rewards. In this paper we study such complex settings, which require reasoning over long time horizons and confront agents with the curse of dimensionality. To deal with the dimensionality, we adopt a Multi-Agent Deep Reinforcement Learning (MA-DRL) approach. We find that when the agents have to make critical decisions in seclusion, existing methods succumb to a combination of relative overgeneralisation (a type of action shadowing), the alter-exploration problem, and the stochasticity. To address these pathologies we introduce expanding negative update intervals that enable independent learners to establish the near-optimal average utility values for higher-level strategies while largely discarding transitions from episodes that result in mis-coordination. We evaluate Negative Update Intervals Double-DQN (NUI-DDQN) within a temporally extended Climb Game, a normal form game which has frequently been used to study relative over-generalisation and other pathologies. We show that NUI-DDQN can converge towards optimal joint-policies in deterministic and stochastic reward settings, overcoming relative-overgeneralisation and the alter-exploration problem while mitigating the moving target problem.

##### Abstract (translated by Google)
在多智能体强化学习中，独立的合作学习者必须克服许多病症才能学习最佳的联合策略。这些病症包括动作阴影，随机性，移动目标和改变探索问题（Matignon，Laurent和Le Fort-Piat 2012; Wei和Luke 2016）。已经提出了许多方法来解决这些病症，但是评估主要在重复的战略形式游戏和仅由少量状态转换组成的随机游戏中进行。这就提出了方法的可扩展性问题，即具有随机转换和奖励的复杂的，时间扩展的，部分可观察的域。在本文中，我们研究了这样复杂的设置，这需要在很长一段时间内进行推理，并且需要面对具有维数诅咒的代理人。为了处理维度，我们采用了多智能体深度强化学习（MA-DRL）方法。我们发现，当代理人必须在隐居中做出关键决策时，现有方法会屈服于相对过度概括（一种动作阴影），变更探索问题和随机性的组合。为了解决这些病症，我们引入了扩展的负更新间隔，使独立学习者能够为更高级别的策略建立接近最优的平均效用值，同时在很大程度上放弃导致错误协调的事件的过渡。我们在时间延长的攀爬游戏中评估负更新间隔Double-DQN（NUI-DDQN），这是一种常规形式的游戏，经常用于研究相对过度泛化和其他病理。我们证明NUI-DDQN可以在确定性和随机奖励设置中收敛于最优联合策略，克服相对过度概括和变更探索问题，同时减轻移动目标问题。

##### URL
[http://arxiv.org/abs/1809.05096](http://arxiv.org/abs/1809.05096)

##### PDF
[http://arxiv.org/pdf/1809.05096](http://arxiv.org/pdf/1809.05096)

