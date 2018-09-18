---
layout: post
title: "Incorporating Behavioral Constraints in Online AI Systems"
date: 2018-09-15 14:24:37
categories: arXiv_AI
tags: arXiv_AI
author: Avinash Balakrishnan, Djallel Bouneffouf, Nicholas Mattei, Francesca Rossi
mathjax: true
---

* content
{:toc}

##### Abstract
AI systems that learn through reward feedback about the actions they take are increasingly deployed in domains that have significant impact on our daily life. However, in many cases the online rewards should not be the only guiding criteria, as there are additional constraints and/or priorities imposed by regulations, values, preferences, or ethical principles. We detail a novel online agent that learns a set of behavioral constraints by observation and uses these learned constraints as a guide when making decisions in an online setting while still being reactive to reward feedback. To define this agent, we propose to adopt a novel extension to the classical contextual multi-armed bandit setting and we provide a new algorithm called Behavior Constrained Thompson Sampling (BCTS) that allows for online learning while obeying exogenous constraints. Our agent learns a constrained policy that implements the observed behavioral constraints demonstrated by a teacher agent, and then uses this constrained policy to guide the reward-based online exploration and exploitation. We characterize the upper bound on the expected regret of the contextual bandit algorithm that underlies our agent and provide a case study with real world data in two application domains. Our experiments show that the designed agent is able to act within the set of behavior constraints without significantly degrading its overall reward performance.

##### Abstract (translated by Google)
通过奖励反馈了解他们采取的行动的人工智能系统越来越多地部署在对我们日常生活有重大影响的领域。但是，在许多情况下，在线奖励不应该是唯一的指导标准，因为法规，价值观，偏好或道德原则会产生额外的限制和/或优先级。我们详细介绍了一个新的在线代理，该代理通过观察学习一组行为约束，并使用这些学习的约束作为在线设置决策时的指导，同时仍然对奖励反馈做出反应。为了定义这个代理，我们建议对经典的上下文多臂强盗设置采用新的扩展，我们提供一种称为行为约束汤普森抽样（BCTS）的新算法，允许在遵循外生约束的同时进行在线学习。我们的代理人学习了一种约束策略，该策略实现了教师代理所展示的观察到的行为约束，然后使用这种约束策略来指导基于奖励的在线探索和利用。我们描述了作为我们的代理人基础的上下文强盗算法的预期遗憾的上限，并提供了两个应用领域中的真实世界数据的案例研究。我们的实验表明，设计的代理能够在行为约束集中行动，而不会显着降低其整体奖励绩效。

##### URL
[http://arxiv.org/abs/1809.05720](http://arxiv.org/abs/1809.05720)

##### PDF
[http://arxiv.org/pdf/1809.05720](http://arxiv.org/pdf/1809.05720)

