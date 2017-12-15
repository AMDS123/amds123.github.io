---
layout: post
title: "Composite Task-Completion Dialogue Policy Learning via Hierarchical Deep Reinforcement Learning"
date: 2017-07-22 22:23:53
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Baolin Peng, Xiujun Li, Lihong Li, Jianfeng Gao, Asli Celikyilmaz, Sungjin Lee, Kam-Fai Wong
mathjax: true
---

* content
{:toc}

##### Abstract
Building a dialogue agent to fulfill complex tasks, such as travel planning, is challenging because the agent has to learn to collectively complete multiple subtasks. For example, the agent needs to reserve a hotel and book a flight so that there leaves enough time for commute between arrival and hotel check-in. This paper addresses this challenge by formulating the task in the mathematical framework of options over Markov Decision Processes (MDPs), and proposing a hierarchical deep reinforcement learning approach to learning a dialogue manager that operates at different temporal scales. The dialogue manager consists of: (1) a top-level dialogue policy that selects among subtasks or options, (2) a low-level dialogue policy that selects primitive actions to complete the subtask given by the top-level policy, and (3) a global state tracker that helps ensure all cross-subtask constraints be satisfied. Experiments on a travel planning task with simulated and real users show that our approach leads to significant improvements over three baselines, two based on handcrafted rules and the other based on flat deep reinforcement learning.

##### Abstract (translated by Google)
建立一个对话代理来完成诸如旅行计划之类的复杂任务是具有挑战性的，因为代理必须学会共同完成多个子任务。例如，代理人需要预订旅馆并预订航班，以便留下足够的时间用于到达和旅馆登记之间的通勤。本文通过在马尔可夫决策过程（MDPs）选项的数学框架中提出任务来解决这个挑战，并且提出了一种分层深度强化学习方法来学习在不同时间尺度上运行的对话管理器。对话管理器包括：（1）在子任务或选项中选择的顶层对话策略;（2）选择原始动作以完成顶层策略给出的子任务的低级对话策略;以及）全球状态跟踪器，有助于确保所有跨子任务约束得到满足。在模拟和实际用户的旅行计划任务上的实验表明，我们的方法导致三个基线，两个基于手工制定的规则，另一个基于平面深度强化学习的显着改善。

##### URL
[https://arxiv.org/abs/1704.03084](https://arxiv.org/abs/1704.03084)

##### PDF
[https://arxiv.org/pdf/1704.03084](https://arxiv.org/pdf/1704.03084)

