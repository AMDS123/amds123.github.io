---
layout: post
title: "Learning Social Conventions in Markov Games"
date: 2018-06-26 15:46:44
categories: arXiv_AI
tags: arXiv_AI GAN Face Reinforcement_Learning
author: Adam Lerer, Alexander Peysakhovich
mathjax: true
---

* content
{:toc}

##### Abstract
Social conventions - arbitrary ways to organize group behavior - are an important part of social life. Any agent that wants to enter an existing society must be able to learn its conventions (e.g. which side of the road to drive on, which language to speak) from relatively few observations or risk being unable to coordinate with everyone else. We consider the game theoretic framework of David Lewis which views the selection of a social convention as the selection of an equilibrium in a coordination game. We ask how to construct reinforcement learning based agents that can solve the convention learning task in the self-play paradigm: at training time the agent has access to a good model of the environment and a small amount of observations about how individuals in society act. The agent then has to construct a policy that is compatible with the test-time social convention. We study three environments from the literature which have multiple conventions: traffic, communication, and risky coordination. In each of these we observe that adding a small amount of imitation learning during self-play training greatly increases the probability that the strategy found by self-play fits well with the social convention the agent will face at test time. We show that this works even in an environment where standard independent multi-agent RL very rarely finds the correct test-time equilibrium.

##### Abstract (translated by Google)
社会习俗 - 组织集体​​行为的武断方式 - 是社会生活的重要组成部分。任何想要进入现有社会的代理人都必须能够从相对较少的观察中学习其惯例（例如开车的哪一边，哪种语言说话），否则将无法与其他人协调。我们考虑大卫刘易斯的博弈理论框架，将社会习俗的选择视为协调博弈中均衡的选择。我们要求如何构建基于强化学习的智能体，它可以解决自我演奏范式中的习惯性学习任务：在培训时，智能体可以访问良好的环境模型，并且可以获得关于社会个体如何行动的少量观察结果。代理人则必须构建一个与测试时间社交惯例兼容的策略。我们从文献中研究了三种有多种约定的环境：交通，通信和风险协调。我们观察到，在每一种情况下，在自我训练训练过程中添加少量模仿学习大大增加了自我发现策略与测试时代人所面临的社会习俗的相符程度。我们证明，即使在标准独立多智能体RL很少找到正确的测试时间均衡的环境中，这种方法也能正常工作。

##### URL
[http://arxiv.org/abs/1806.10071](http://arxiv.org/abs/1806.10071)

##### PDF
[http://arxiv.org/pdf/1806.10071](http://arxiv.org/pdf/1806.10071)

