---
layout: post
title: "Reinforcement Learning on Web Interfaces Using Workflow-Guided Exploration"
date: 2018-02-24 05:32:47
categories: arXiv_AI
tags: arXiv_AI Sparse Face Reinforcement_Learning
author: Evan Zheran Liu, Kelvin Guu, Panupong Pasupat, Tianlin Shi, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) agents improve through trial-and-error, but when reward is sparse and the agent cannot discover successful action sequences, learning stagnates. This has been a notable problem in training deep RL agents to perform web-based tasks, such as booking flights or replying to emails, where a single mistake can ruin the entire sequence of actions. A common remedy is to "warm-start" the agent by pre-training it to mimic expert demonstrations, but this is prone to overfitting. Instead, we propose to constrain exploration using demonstrations. From each demonstration, we induce high-level "workflows" which constrain the allowable actions at each time step to be similar to those in the demonstration (e.g., "Step 1: click on a textbox; Step 2: enter some text"). Our exploration policy then learns to identify successful workflows and samples actions that satisfy these workflows. Workflows prune out bad exploration directions and accelerate the agent's ability to discover rewards. We use our approach to train a novel neural policy designed to handle the semi-structured nature of websites, and evaluate on a suite of web tasks, including the recent World of Bits benchmark. We achieve new state-of-the-art results, and show that workflow-guided exploration improves sample efficiency over behavioral cloning by more than 100x.

##### Abstract (translated by Google)
强化学习（RL）试剂通过反复试验得到改善，但是当奖励稀少且试剂无法发现成功的动作序列时，学习停滞不前。这在培训深度RL代理人执行基于网络的任务（如预订航班或回复电子邮件）方面是一个值得注意的问题，因为单个错误可能会破坏整个系列的行动。一种常见的补救措施是通过预先训练它来模拟专家示范来“热身”试剂，但这很容易过度拟合。相反，我们建议使用示范来限制探索。从每个演示中，我们引发高层次的“工作流程”，这些“工作流程”在每个时间步骤限制允许的操作与演示中的操作类似（例如，“步骤1：点击文本框;步骤2：输入一些文本”）。我们的探索政策然后学会识别成功的工作流程并采样满足这些工作流程的行为。工作流程会削减不良的探索方向，并加速代理人发现奖励的能力。我们使用我们的方法来训练旨在处理网站半结构性质的新型神经策略，并评估一系列网络任务，包括最近的比特世界标准。我们实现了最新的最先进的结果，并显示工作流引导的探索将行为克隆的样本效率提高了100倍以上。

##### URL
[http://arxiv.org/abs/1802.08802](http://arxiv.org/abs/1802.08802)

##### PDF
[http://arxiv.org/pdf/1802.08802](http://arxiv.org/pdf/1802.08802)

