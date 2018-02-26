---
layout: post
title: "Hindsight Experience Replay"
date: 2018-02-23 10:04:20
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Marcin Andrychowicz, Filip Wolski, Alex Ray, Jonas Schneider, Rachel Fong, Peter Welinder, Bob McGrew, Josh Tobin, Pieter Abbeel, Wojciech Zaremba
mathjax: true
---

* content
{:toc}

##### Abstract
Dealing with sparse rewards is one of the biggest challenges in Reinforcement Learning (RL). We present a novel technique called Hindsight Experience Replay which allows sample-efficient learning from rewards which are sparse and binary and therefore avoid the need for complicated reward engineering. It can be combined with an arbitrary off-policy RL algorithm and may be seen as a form of implicit curriculum. 
 We demonstrate our approach on the task of manipulating objects with a robotic arm. In particular, we run experiments on three different tasks: pushing, sliding, and pick-and-place, in each case using only binary rewards indicating whether or not the task is completed. Our ablation studies show that Hindsight Experience Replay is a crucial ingredient which makes training possible in these challenging environments. We show that our policies trained on a physics simulation can be deployed on a physical robot and successfully complete the task.

##### Abstract (translated by Google)
处理稀疏奖励是强化学习（RL）中最大的挑战之一。我们提出了一种称为事后体验回放的新技术，它允许从稀疏和二元的奖励中进行样本高效的学习，因此避免了对复杂奖励工程的需求。它可以与任意的关闭策略RL算法相结合，并且可以被看作是隐式课程的一种形式。
 我们展示了用机器人手臂操纵物体的任务。特别是，我们在三个不同的任务上进行实验：推送，滑动和拾放，每种情况下只使用二进制奖励来指示任务是否完成。我们的消融研究表明，事后体验回放是在这些具有挑战性的环境中使培训成为可能的关键因素。我们表明，我们的物理仿真培训策略可以部署在物理机器人上并成功完成任务。

##### URL
[http://arxiv.org/abs/1707.01495](http://arxiv.org/abs/1707.01495)

##### PDF
[http://arxiv.org/pdf/1707.01495](http://arxiv.org/pdf/1707.01495)

