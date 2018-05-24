---
layout: post
title: "Reinforcement Learning for Heterogeneous Teams with PALO Bounds"
date: 2018-05-23 16:27:51
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Roi Ceren, Prashant Doshi, Keyang He
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce reinforcement learning for heterogeneous teams in which rewards for an agent are additively factored into local costs, stimuli unique to each agent, and global rewards, those shared by all agents in the domain. Motivating domains include coordination of varied robotic platforms, which incur different costs for the same action, but share an overall goal. We present two templates for learning in this setting with factored rewards: a generalization of Perkins' Monte Carlo exploring starts for POMDPs to canonical MPOMDPs, with a single policy mapping joint observations of all agents to joint actions (MCES-MP); and another with each agent individually mapping joint observations to their own action (MCES-FMP). We use probably approximately local optimal (PALO) bounds to analyze sample complexity, instantiating these templates to PALO learning. We promote sample efficiency by including a policy space pruning technique, and evaluate the approaches on three domains of heterogeneous agents demonstrating that MCES-FMP yields improved policies in less samples compared to MCES-MP and a previous benchmark.

##### Abstract (translated by Google)
我们为异构团队引入了强化学习，其中代理人的奖励被加入到本地成本中，每个代理程序独特的刺激因素以及域中所有代理程序共享的全局奖励。激励领域包括协调各种机器人平台，对同一行动产生不同的成本，但共享一个总体目标。我们提出了两种用于学习的模板，其中包含了分解奖励：珀金斯蒙特卡洛探索的推广开始于POMDPs到典型MPOMDPs，一个策略映射所有代理对联合行动的联合观测（MCES-MP）;另一个与每个代理分别映射联合观测到他们自己的行动（MCES-FMP）。我们可能使用近似局部最优（PALO）边界来分析样本的复杂性，将这些模板实例化为PALO学习。我们通过引入策略空间修剪技术来提高样本效率，并评估异构代理的三个领域的方法，证明MCES-FMP与MCES-MP和之前的基准相比，在更少的样本中产生改进的策略。

##### URL
[http://arxiv.org/abs/1805.09267](http://arxiv.org/abs/1805.09267)

##### PDF
[http://arxiv.org/pdf/1805.09267](http://arxiv.org/pdf/1805.09267)

