---
layout: post
title: "ARCHER: Aggressive Rewards to Counter bias in Hindsight Experience Replay"
date: 2018-09-06 16:08:39
categories: arXiv_AI
tags: arXiv_AI Sparse Face Reinforcement_Learning
author: Sameera Lanka, Tianfu Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Experience replay is an important technique for addressing sample-inefficiency in deep reinforcement learning (RL), but faces difficulty in learning from binary and sparse rewards due to disproportionately few successful experiences in the replay buffer. Hindsight experience replay (HER) was recently proposed to tackle this difficulty by manipulating unsuccessful transitions, but in doing so, HER introduces a significant bias in the replay buffer experiences and therefore achieves a suboptimal improvement in sample-efficiency. In this paper, we present an analysis on the source of bias in HER, and propose a simple and effective method to counter the bias, to most effectively harness the sample-efficiency provided by HER. Our method, motivated by counter-factual reasoning and called ARCHER, extends HER with a trade-off to make rewards calculated for hindsight experiences numerically greater than real rewards. We validate our algorithm on two continuous control environments from DeepMind Control Suite - Reacher and Finger, which simulate manipulation tasks with a robotic arm - in combination with various reward functions, task complexities and goal sampling strategies. Our experiments consistently demonstrate that countering bias using more aggressive hindsight rewards increases sample efficiency, thus establishing the greater benefit of ARCHER in RL applications with limited computing budget.

##### Abstract (translated by Google)
体验重放是解决深度强化学习（RL）中样本效率低下的一种重要技术，但由于重放缓冲区中成功经验不成比例，因此难以学习二进制和稀疏奖励。最近提出后见之明体验重播（HER）通过操纵不成功的转换来解决这一困难，但是在这样做时，HER在重放缓冲体验中引入了显着偏差，因此实现了样本效率的次优改进。在本文中，我们对HER中的偏差来源进行了分析，并提出了一种简单有效的方法来对抗偏差，从而最有效地利用HER提供的样本效率。我们的方法，以反事实推理为动机，并称为ARCHER，通过权衡来扩展HER，以便为事后体验计算出的奖励数值大于实际奖励。我们在DeepMind Control Suite的两个连续控制环境中验证我们的算法 -  Reacher和Finger，它使用机械臂模拟操作任务 - 结合各种奖励功能，任务复杂性和目标抽样策略。我们的实验一致表明，使用更积极的后见之明奖励来抵消偏差会提高样本效率，从而在计算预算有限的RL应用中建立ARCHER的更大优势。

##### URL
[http://arxiv.org/abs/1809.02070](http://arxiv.org/abs/1809.02070)

##### PDF
[http://arxiv.org/pdf/1809.02070](http://arxiv.org/pdf/1809.02070)

