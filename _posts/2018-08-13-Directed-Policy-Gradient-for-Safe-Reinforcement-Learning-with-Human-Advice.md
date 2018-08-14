---
layout: post
title: "Directed Policy Gradient for Safe Reinforcement Learning with Human Advice"
date: 2018-08-13 08:12:22
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: H&#xe9;l&#xe8;ne Plisnier, Denis Steckelmacher, Tim Brys, Diederik M. Roijers, Ann Now&#xe9;
mathjax: true
---

* content
{:toc}

##### Abstract
Many currently deployed Reinforcement Learning agents work in an environment shared with humans, be them co-workers, users or clients. It is desirable that these agents adjust to people's preferences, learn faster thanks to their help, and act safely around them. We argue that most current approaches that learn from human feedback are unsafe: rewarding or punishing the agent a-posteriori cannot immediately prevent it from wrong-doing. In this paper, we extend Policy Gradient to make it robust to external directives, that would otherwise break the fundamentally on-policy nature of Policy Gradient. Our technique, Directed Policy Gradient (DPG), allows a teacher or backup policy to override the agent before it acts undesirably, while allowing the agent to leverage human advice or directives to learn faster. Our experiments demonstrate that DPG makes the agent learn much faster than reward-based approaches, while requiring an order of magnitude less advice.

##### Abstract (translated by Google)
许多当前部署的强化学习代理在与人共享的环境中工作，无论是同事，用户还是客户。这些代理人希望能够适应人们的喜好，通过他们的帮助更快地学习，并在他们周围安全地行动。我们认为，从人类反馈中学习的大多数方法都是不安全的：奖励或惩罚代理人后来不能立即阻止它做错事。在本文中，我们扩展了Policy Gradient，使其对外部指令具有鲁棒性，否则会破坏Policy Gradient的基本政策性质。我们的技术Directed Policy Gradient（DPG）允许教师或备份策略在代理不受欢迎之前覆盖代理，同时允许代理利用人工建议或指令更快地学习。我们的实验表明，DPG使得代理学习的速度比基于奖励的方法快得多，同时需要一个数量级的建议。

##### URL
[http://arxiv.org/abs/1808.04096](http://arxiv.org/abs/1808.04096)

##### PDF
[http://arxiv.org/pdf/1808.04096](http://arxiv.org/pdf/1808.04096)

