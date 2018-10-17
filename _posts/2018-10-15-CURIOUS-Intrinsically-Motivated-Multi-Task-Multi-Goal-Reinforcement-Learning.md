---
layout: post
title: "CURIOUS: Intrinsically Motivated Multi-Task, Multi-Goal Reinforcement Learning"
date: 2018-10-15 11:40:28
categories: arXiv_AI
tags: arXiv_AI Attention Face Reinforcement_Learning
author: Cédric Colas, Olivier Sigaud, Pierre-Yves Oudeyer
mathjax: true
---

* content
{:toc}

##### Abstract
In open-ended and changing environments, agents face a wide range of potential tasks that may or may not come with associated reward functions. Such autonomous learning agents must be able to generate their own tasks through a process of intrinsically motivated exploration, some of which might prove easy, others impossible. For this reason, they should be able to actively select which task to practice at any given moment, to maximize their overall mastery on the set of learnable tasks. This paper proposes CURIOUS, an extension of Universal Value Function Approximators that enables intrinsically motivated agents to learn to achieve both multiple tasks and multiple goals within a unique policy, leveraging hindsight learning. Agents focus on achievable tasks first, using an automated curriculum learning mechanism that biases their attention towards tasks maximizing the absolute learning progress. This mechanism provides robustness to catastrophic forgetting (by refocusing on tasks where performance decreases) and distracting tasks (by avoiding tasks with no absolute learning progress). Furthermore, we show that having two levels of parameterization (tasks and goals within tasks) enables more efficient learning of skills in an environment with a modular physical structure (e.g. multiple objects) as compared to flat, goal-parameterized RL with hindsight experience replay.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.06284](https://arxiv.org/abs/1810.06284)

##### PDF
[https://arxiv.org/pdf/1810.06284](https://arxiv.org/pdf/1810.06284)

