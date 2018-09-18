---
layout: post
title: "Learning to Collaborate: Multi-Scenario Ranking via Multi-Agent Reinforcement Learning"
date: 2018-09-17 14:45:21
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Relation Recommendation
author: Jun Feng, Heng Li, Minlie Huang, Shichen Liu, Wenwu Ou, Zhirong Wang, Xiaoyan Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Ranking is a fundamental and widely studied problem in scenarios such as search, advertising, and recommendation. However, joint optimization for multi-scenario ranking, which aims to improve the overall performance of several ranking strategies in different scenarios, is rather untouched. Separately optimizing each individual strategy has two limitations. The first one is lack of collaboration between scenarios meaning that each strategy maximizes its own objective but ignores the goals of other strategies, leading to a sub-optimal overall performance. The second limitation is the inability of modeling the correlation between scenarios meaning that independent optimization in one scenario only uses its own user data but ignores the context in other scenarios. 
 In this paper, we formulate multi-scenario ranking as a fully cooperative, partially observable, multi-agent sequential decision problem. We propose a novel model named Multi-Agent Recurrent Deterministic Policy Gradient (MA-RDPG) which has a communication component for passing messages, several private actors (agents) for making actions for ranking, and a centralized critic for evaluating the overall performance of the co-working actors. Each scenario is treated as an agent (actor). Agents collaborate with each other by sharing a global action-value function (the critic) and passing messages that encodes historical information across scenarios. The model is evaluated with online settings on a large E-commerce platform. Results show that the proposed model exhibits significant improvements against baselines in terms of the overall performance.

##### Abstract (translated by Google)
在搜索，广告和推荐等场景中，排名是一个基础且广泛研究的问题。然而，多场景排名的联合优化，旨在提高不同场景中几种排名策略的整体表现，相当不受影响。单独优化每个单独的策略有两个限制。第一个是场景之间缺乏协作，这意味着每个策略最大化其自身目标，但忽略了其他策略的目标，导致次优的整体表现。第二个限制是无法对场景之间的相关性进行建模，这意味着一个场景中的独立优化仅使用其自己的用户数据，而忽略了其他场景中的上下文。
 在本文中，我们将多场景排名表示为完全合作，部分可观察，多智能体的顺序决策问题。我们提出了一个名为Multi-Agent Recurrent Deterministic Policy Gradient（MA-RDPG）的新模型，它有一个用于传递消息的通信组件，几个私人参与者（代理人）用于进行排名操作，以及一个集中评论员用于评估整体性能。共同工作的演员。每个场景都被视为代理（actor）。代理通过共享全局动作 - 值函数（批评者）并传递跨场景编码历史信息的消息来相互协作。该模型使用大型电子商务平台上的在线设置进行评估。结果表明，所提出的模型在整体性能方面显示出对基线的显着改善。

##### URL
[http://arxiv.org/abs/1809.06260](http://arxiv.org/abs/1809.06260)

##### PDF
[http://arxiv.org/pdf/1809.06260](http://arxiv.org/pdf/1809.06260)

