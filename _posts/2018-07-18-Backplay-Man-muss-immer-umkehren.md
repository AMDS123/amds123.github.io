---
layout: post
title: "Backplay: 'Man muss immer umkehren'"
date: 2018-07-18 13:28:59
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Cinjon Resnick, Roberta Raileanu, Sanyam Kapoor, Alex Peysakhovich, Kyunghyun Cho, Joan Bruna
mathjax: true
---

* content
{:toc}

##### Abstract
A long-standing problem in model free reinforcement learning (RL) is that it requires a large number of trials to learn a good policy, especially in environments with sparse rewards. We explore a method to increase the sample efficiency of RL when we have access to demonstrations. Our approach, which we call Backplay, uses a single demonstration to construct a curriculum for a given task. Rather than starting each training episode in the environment's fixed initial state, we start the agent near the end of the demonstration and move the starting point backwards during the course of training until we reach the initial state. We perform experiments in a competitive four player game (Pommerman) and a path-finding maze game. We find that this weak form of guidance provides significant gains in sample complexity with a stark advantage in sparse reward environments. In some cases, standard RL did not yield any improvement while Backplay reached success rates greater than 50% and generalized to unseen initial conditions in the same amount of training time. Additionally, we see that agents trained via Backplay can learn policies superior to those of the original demonstration.

##### Abstract (translated by Google)
模型自由强化学习（RL）中一个长期存在的问题是，它需要大量的试验来学习一个好的政策，特别是在奖励稀疏的环境中。我们探索了一种方法，可以在我们访问演示时提高RL的样本效率。我们的方法，我们称之为Backplay，使用单个演示来构建给定任务的课程。我们不是在环境固定的初始状态下开始每个训练集，而是在演示结束时启动代理，并在训练过程中向后移动起点，直到我们达到初始状态。我们在竞争激烈的四人游戏（Pommerman）和寻路迷宫游戏中进行实验。我们发现，这种微弱的指导形式在样本复杂性方面取得了显着的进步，在稀疏奖励环境中具有明显的优势。在某些情况下，标准RL没有产生任何改善，而Backplay的成功率大于50％，并且在相同的训练时间内推广到看不见的初始条件。此外，我们看到通过Backplay训练的代理可以学习优于原始演示的策略。

##### URL
[https://arxiv.org/abs/1807.06919](https://arxiv.org/abs/1807.06919)

##### PDF
[https://arxiv.org/pdf/1807.06919](https://arxiv.org/pdf/1807.06919)

