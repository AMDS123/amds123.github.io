---
layout: post
title: "Unsupervised Perceptual Rewards for Imitation Learning"
date: 2017-06-12 21:38:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning Quantitative
author: Pierre Sermanet, Kelvin Xu, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Reward function design and exploration time are arguably the biggest obstacles to the deployment of reinforcement learning (RL) agents in the real world. In many real-world tasks, designing a reward function takes considerable hand engineering and often requires additional sensors to be installed just to measure whether the task has been executed successfully. Furthermore, many interesting tasks consist of multiple implicit intermediate steps that must be executed in sequence. Even when the final outcome can be measured, it does not necessarily provide feedback on these intermediate steps. To address these issues, we propose leveraging the abstraction power of intermediate visual representations learned by deep models to quickly infer perceptual reward functions from small numbers of demonstrations. We present a method that is able to identify key intermediate steps of a task from only a handful of demonstration sequences, and automatically identify the most discriminative features for identifying these steps. This method makes use of the features in a pre-trained deep model, but does not require any explicit specification of sub-goals. The resulting reward functions can then be used by an RL agent to learn to perform the task in real-world settings. To evaluate the learned reward, we present qualitative results on two real-world tasks and a quantitative evaluation against a human-designed reward function. We also show that our method can be used to learn a real-world door opening skill using a real robot, even when the demonstration used for reward learning is provided by a human using their own hand. To our knowledge, these are the first results showing that complex robotic manipulation skills can be learned directly and without supervised labels from a video of a human performing the task. Supplementary material and data are available at this https URL

##### Abstract (translated by Google)
奖励功能设计和探索时间可以说是在现实世界中部署强化学习（RL）代理的最大障碍。在许多现实世界的任务中，设计奖励功能需要大量的手工设计，并且通常需要安装额外的传感器来测量任务是否成功执行。此外，许多有趣的任务由多个隐含的中间步骤组成，必须按顺序执行。即使最后的结果可以衡量，它也不一定提供这些中间步骤的反馈。为了解决这些问题，我们提出利用深层模型学习的中间视觉表示的抽象能力来快速从少量的示范中推断出感知的回报函数。我们提出了一种能够从少数示范序列中识别任务的关键中间步骤的方法，并自动识别用于识别这些步骤的最具有区别性的特征。该方法利用预先训练的深层模型中的特征，但不需要任何明确的子目标指定。由此产生的奖励函数可以被RL代理人用来学习在真实世界的设置中执行任务。为了评估学习到的奖励，我们给出两个真实世界任务的定性结果和一个人类设计奖励函数的定量评估。我们还显示，即使用于奖励学习的演示是由人类用自己的手提供的，我们的方法也可以用于使用真实机器人学习真实的开门技巧。据我们所知，这是第一个结果，表明复杂的机器人操纵技能可以直接学习，而不需要从执行任务的人的视频监督标签。补充材料和数据可在此https网址获得

##### URL
[https://arxiv.org/abs/1612.06699](https://arxiv.org/abs/1612.06699)

##### PDF
[https://arxiv.org/pdf/1612.06699](https://arxiv.org/pdf/1612.06699)

