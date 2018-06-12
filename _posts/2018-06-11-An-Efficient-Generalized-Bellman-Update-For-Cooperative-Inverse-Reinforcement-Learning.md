---
layout: post
title: "An Efficient, Generalized Bellman Update For Cooperative Inverse Reinforcement Learning"
date: 2018-06-11 06:06:43
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Dhruv Malik, Malayandi Palaniappan, Jaime F. Fisac, Dylan Hadfield-Menell, Stuart Russell, Anca D. Dragan
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal is for AI systems to correctly identify and act according to their human user's objectives. Cooperative Inverse Reinforcement Learning (CIRL) formalizes this value alignment problem as a two-player game between a human and robot, in which only the human knows the parameters of the reward function: the robot needs to learn them as the interaction unfolds. Previous work showed that CIRL can be solved as a POMDP, but with an action space size exponential in the size of the reward parameter space. In this work, we exploit a specific property of CIRL---the human is a full information agent---to derive an optimality-preserving modification to the standard Bellman update; this reduces the complexity of the problem by an exponential factor and allows us to relax CIRL's assumption of human rationality. We apply this update to a variety of POMDP solvers and find that it enables us to scale CIRL to non-trivial problems, with larger reward parameter spaces, and larger action spaces for both robot and human. In solutions to these larger problems, the human exhibits pedagogic (teaching) behavior, while the robot interprets it as such and attains higher value for the human.

##### Abstract (translated by Google)
我们的目标是让AI系统根据其用户的目标正确识别并采取行动。合作逆向强化学习（CIRL）将这种价值对准问题形式化为人与机器人之间的双人游戏，其中只有人类知道奖励函数的参数：机器人需要在交互展开时学习它们。以前的工作表明，CIRL可以作为一个POMDP解决，但行动空间大小指数的奖励参数空间的大小。在这项工作中，我们利用CIRL的一个特定属性---人是一个完整的信息代理---为标准的Bellman更新推导一个保持最优性的修改;这通过指数因子降低了问题的复杂性，并使我们能够放宽CIRL对人类理性的假设。我们将这一更新应用于各种POMDP解算器，并发现它使我们能够将CIRL扩展为非平凡的问题，具有较大的回报参数空间以及机器人和人类更大的动作空间。在解决这些较大问题的方法中，人类表现出教学（教学）行为，而机器人则是这样解释并为人类创造更高的价值。

##### URL
[http://arxiv.org/abs/1806.03820](http://arxiv.org/abs/1806.03820)

##### PDF
[http://arxiv.org/pdf/1806.03820](http://arxiv.org/pdf/1806.03820)

