---
layout: post
title: "Learning Existing Social Conventions in Markov Games"
date: 2018-09-04 15:21:52
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Adam Lerer, Alexander Peysakhovich
mathjax: true
---

* content
{:toc}

##### Abstract
In order for artificial agents to coordinate effectively with people, they must act consistently with existing conventions (e.g. how to navigate in traffic, which language to speak, or how to work with teammates). A group's conventions can be viewed as a choice of equilibrium in a coordination game. We consider the problem of an agent learning a policy for a coordination game in a simulated environment and then using this policy when it enters an existing group. When there are multiple possible conventions we show that learning a policy via multi-agent reinforcement learning (MARL) is likely to find policies which achieve high payoffs at training time but fail to coordinate with the real group into which the agent enters. We assume access to a small number of samples of behavior from the true convention and show that we can augment the MARL objective to help it find policies consistent with the real group's convention. In three environments from the literature - traffic, communication, and team coordination - we observe that augmenting MARL with a small amount of imitation learning greatly increases the probability that the strategy found by MARL fits well with the existing social convention. We show that this works even in an environment where standard training methods very rarely find the true convention of the agent's partners.

##### Abstract (translated by Google)
为了使人工代理人与人有效协调，他们必须与现有惯例保持一致（例如，如何在交通中导航，使用哪种语言或如何与队友合作）。小组的惯例可以被视为协调游戏中的均衡选择。我们考虑代理在模拟环境中学习协调游戏策略的问题，然后在进入现有组时使用该策略。当存在多种可能的约定时，我们表明通过多智能体强化学习（MARL）学习策略可能会找到在训练时获得高回报但未能与代理进入的真实组协调的策略。我们假设从真正的约定中访问少量行为样本，并表明我们可以扩充MARL目标，以帮助它找到符合实际组约定的策略。在文学的三个环境中 - 交通，沟通和团队协调 - 我们观察到用少量的模仿学习来增加MARL大大增加了MARL发现的策略与现有社会习俗很好地契合的可能性。我们证明，即使在标准培训方法很少找到代理商合作伙伴的真实惯例的环境中，这也是有效的。

##### URL
[http://arxiv.org/abs/1806.10071](http://arxiv.org/abs/1806.10071)

##### PDF
[http://arxiv.org/pdf/1806.10071](http://arxiv.org/pdf/1806.10071)

