---
layout: post
title: "Impossibility of deducing preferences and rationality from human policy"
date: 2017-12-15 19:05:01
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Stuart Armstrong, S&#xf6;ren Mindermann
mathjax: true
---

* content
{:toc}

##### Abstract
Inverse reinforcement learning (IRL) attempts to infer human rewards or preferences from observed behavior. However, human planning systematically deviates from rationality. Though there has been some IRL work which assumes humans are noisily rational, there has been little analysis of the general problem of inferring the reward of a human of unknown rationality. The observed behavior can, in principle, be decomposed into two composed into two components: a reward function and a planning algorithm that maps reward function to policy. Both of these variables have to be inferred from behaviour. This paper presents a "No Free Lunch" theorem in this area, showing that, without making `normative' assumptions beyond the data, nothing about the human reward function can be deduced from human behaviour. Unlike most No Free Lunch theorems, this cannot be alleviated by regularising with simplicity assumptions. The simplest hypotheses are generally degenerate. The paper will then sketch how one might begin to use normative assumptions to get around the problem, without which solving the general IRL problem is impossible. The reward function-planning algorithm formalism can also be used to encode what it means for an agent to manipulate or override human preferences.

##### Abstract (translated by Google)
逆强化学习（IRL）尝试从观察到的行为中推断人类的奖励或偏好。然而，人的计划系统地偏离合理性。虽然有一些IRL工作假设人类是理性的，但是对于推断理性不明的人的奖励的一般问题却很少有分析。观察到的行为原则上可以被分解为两部分：一个奖励函数和一个将奖励函数映射到策略的计划算法。这两个变量都必须从行为推断出来。本文提出了这个领域的“免费午餐”定理，表明在没有超出数据范围的“规范”假设的情况下，人类的行为就不能推导出人类的奖励函数。不同于大多数免费午餐定理，这不能通过用简单的假设进行规则化来缓解。最简单的假设通常是退化的。本文将描述如何开始使用规范假设来解决问题，否则解决一般的IRL问题是不可能的。奖励函数规划算法形式也可以用来编码代理人操纵或超越人类偏好的意义。

##### URL
[http://arxiv.org/abs/1712.05812](http://arxiv.org/abs/1712.05812)

##### PDF
[http://arxiv.org/pdf/1712.05812](http://arxiv.org/pdf/1712.05812)

