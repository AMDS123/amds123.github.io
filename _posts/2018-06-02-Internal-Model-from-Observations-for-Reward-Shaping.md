---
layout: post
title: "Internal Model from Observations for Reward Shaping"
date: 2018-06-02 08:15:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Daiki Kimura, Subhajit Chaudhury, Ryuki Tachibana, Sakyasingha Dasgupta
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning methods require careful design involving a reward function to obtain the desired action policy for a given task. In the absence of hand-crafted reward functions, prior work on the topic has proposed several methods for reward estimation by using expert state trajectories and action pairs. However, there are cases where complete or good action information cannot be obtained from expert demonstrations. We propose a novel reinforcement learning method in which the agent learns an internal model of observation on the basis of expert-demonstrated state trajectories to estimate rewards without completely learning the dynamics of the external environment from state-action pairs. The internal model is obtained in the form of a predictive model for the given expert state distribution. During reinforcement learning, the agent predicts the reward as a function of the difference between the actual state and the state predicted by the internal model. We conducted multiple experiments in environments of varying complexity, including the Super Mario Bros and Flappy Bird games. We show our method successfully trains good policies directly from expert game-play videos.

##### Abstract (translated by Google)
强化学习方法需要包含奖励功能的谨慎设计，以获得针对给定任务的期望行动策略。在缺乏手工奖励功能的情况下，以前关于该主题的工作已经提出了几种使用专家状态轨迹和行为对进行奖励评估的方法。但是，有些情况下无法从专家示范中获得完整或良好的行动信息。我们提出了一种新的强化学习方法，其中代理人在专家演示的状态轨迹的基础上学习内部观察模型来估计奖励，而无需从状态行为对中完全学习外部环境的动态。内部模型是以给定专家状态分布的预测模型的形式获得的。在强化学习期间，代理人将奖励预测为实际状态与内部模型预测的状态之间的差异的函数。我们在不同复杂程度的环境中进行了多项实验，包括超级马里奥兄弟和Flappy Bird游戏。我们展示了我们的方法成功地直接从专家游戏播放视频培训了良好的政策。

##### URL
[http://arxiv.org/abs/1806.01267](http://arxiv.org/abs/1806.01267)

##### PDF
[http://arxiv.org/pdf/1806.01267](http://arxiv.org/pdf/1806.01267)

