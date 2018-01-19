---
layout: post
title: "Integrating planning for task-completion dialogue policy learning"
date: 2018-01-18 18:57:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Baolin Peng, Xiujun Li, Jianfeng Gao, Jingjing Liu, Kam-Fai Wong
mathjax: true
---

* content
{:toc}

##### Abstract
Training a task-completion dialogue agent with real users via reinforcement learning (RL) could be prohibitively expensive, because it requires many interactions with users. One alternative is to resort to a user simulator, while the discrepancy of between simulated and real users makes the learned policy unreliable in practice. This paper addresses these challenges by integrating planning into the dialogue policy learning based on Dyna-Q framework, and provides a more sample-efficient approach to learn the dialogue polices. The proposed agent consists of a planner trained on-line with limited real user experience that can generate large amounts of simulated experience to supplement with limited real user experience, and a policy model trained on these hybrid experiences. The effectiveness of our approach is validated on a movie-booking task in both a simulation setting and a human-in-the-loop setting.

##### Abstract (translated by Google)
通过强化学习（RL）与真实用户培训任务完成对话代理可能会非常昂贵，因为它需要与用户进行许多交互。另一种方法是求助于用户模拟器，而模拟用户和真实用户之间的差异使得学习策略在实践中不可靠。本文通过将规划整合到基于Dyna-Q框架的对话政策学习中来解决这些挑战，并为学习对话政策提供了更有效的样本方法。提出的代理包括一个在线培训的有限实际用户体验的规划师，可以产生大量的模拟经验来补充有限的真实用户体验，以及一个培训这些混合体验的策略模型。我们的方法的有效性在模拟设置和人在回路设置中的电影预订任务上得到验证。

##### URL
[http://arxiv.org/abs/1801.06176](http://arxiv.org/abs/1801.06176)

##### PDF
[http://arxiv.org/pdf/1801.06176](http://arxiv.org/pdf/1801.06176)

