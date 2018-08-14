---
layout: post
title: "Learning Task Specifications from Demonstrations"
date: 2018-08-13 00:32:09
categories: arXiv_AI
tags: arXiv_AI Inference
author: Marcell Vazquez-Chanlatte, Susmit Jha, Ashish Tiwari, Sanjit A. Seshia
mathjax: true
---

* content
{:toc}

##### Abstract
Real world applications often naturally decompose into several sub-tasks. In many settings (e.g., robotics) demonstrations provide a natural way to specify the sub-tasks. However, most methods for learning from demonstrations either do not provide guarantees that the artifacts learned for the subtasks can be safely recombined or limit the types of composition available. Motivated by this deficit, we consider the problem of inferring binary non-Markovian rewards, also known as logical trace properties or \emph{specifications}, from demonstrations provided by an agent operating in an uncertain, stochastic environment. Crucially, specifications admit well-defined composition rules that are typically easy to interpret. In this paper, we formulate the specification inference task as a maximum a posteriori (MAP) probability inference problem, apply the principle of maximum entropy to derive an analytic demonstration likelihood model and give an efficient approach to search for the most likely specification in a large candidate pool of specifications. In our experiments, we demonstrate how learning specifications can help avoid common bugs that often occur due to ad-hoc reward composition.

##### Abstract (translated by Google)
真实世界的应用程序通常会自然地分解为几个子任务。在许多设置（例如，机器人技术）中，演示提供了指定子任务的自然方式。但是，大多数从演示中学习的方法都不能保证为子任务学习的工件可以安全地重新组合或限制可用的组合类型。受到这种不足的影响，我们考虑了在不确定的随机环境中运行的代理提供的演示推断二元非马尔可夫奖励的问题，也称为逻辑跟踪属性或\ emph {规范}。至关重要的是，规范允许明确定义的组合规则，这些规则通常易于理解。在本文中，我们将规范推理任务表示为最大后验概率推理问题，应用最大熵原理推导出一个解析证明似然模型，并提供一种有效的方法来搜索大的最可能的规范。候选人规范库。在我们的实验中，我们演示了学习规范如何帮助避免由于临时奖励组合而经常发生的常见错误。

##### URL
[http://arxiv.org/abs/1710.03875](http://arxiv.org/abs/1710.03875)

##### PDF
[http://arxiv.org/pdf/1710.03875](http://arxiv.org/pdf/1710.03875)

