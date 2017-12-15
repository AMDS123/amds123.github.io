---
layout: post
title: "Towards End-to-End Reinforcement Learning of Dialogue Agents for Information Access"
date: 2017-04-20 17:26:35
categories: arXiv_CL
tags: arXiv_CL Knowledge Reinforcement_Learning
author: Bhuwan Dhingra, Lihong Li, Xiujun Li, Jianfeng Gao, Yun-Nung Chen, Faisal Ahmed, Li Deng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes KB-InfoBot -- a multi-turn dialogue agent which helps users search Knowledge Bases (KBs) without composing complicated queries. Such goal-oriented dialogue agents typically need to interact with an external database to access real-world knowledge. Previous systems achieved this by issuing a symbolic query to the KB to retrieve entries based on their attributes. However, such symbolic operations break the differentiability of the system and prevent end-to-end training of neural dialogue agents. In this paper, we address this limitation by replacing symbolic queries with an induced "soft" posterior distribution over the KB that indicates which entities the user is interested in. Integrating the soft retrieval process with a reinforcement learner leads to higher task success rate and reward in both simulations and against real users. We also present a fully neural end-to-end agent, trained entirely from user feedback, and discuss its application towards personalized dialogue agents. The source code is available at this https URL

##### Abstract (translated by Google)
本文提出了KB-InfoBot  - 一个多回合对话代理，它可以帮助用户搜索知识库（Knowledge Base，KB），而不需要编写复杂的查询。这种面向目标的对话代理通常需要与外部数据库交互以访问真实世界的知识。以前的系统通过向KB发出符号查询以基于其属性检索条目来实现这一点。然而，这样的符号操作打破了系统的可微性，阻碍了神经对话剂的端对端训练。在本文中，我们解决了这个限制，通过在知识库中引用“软”后验分布来替代符号查询，指出用户感兴趣的实体。将软检索过程与强化学习者结合，可以获得更高的任务成功率和奖励在模拟和真实的用户。我们还提供了一个完全由用户反馈训练的完全神经端对端代理，并讨论它在个性化对话代理中的应用。源代码可在此https URL中获得

##### URL
[https://arxiv.org/abs/1609.00777](https://arxiv.org/abs/1609.00777)

##### PDF
[https://arxiv.org/pdf/1609.00777](https://arxiv.org/pdf/1609.00777)

