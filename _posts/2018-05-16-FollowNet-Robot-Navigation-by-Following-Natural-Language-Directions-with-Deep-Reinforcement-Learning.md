---
layout: post
title: "FollowNet: Robot Navigation by Following Natural Language Directions with Deep Reinforcement Learning"
date: 2018-05-16 06:29:18
categories: arXiv_RO
tags: arXiv_RO Sparse Attention Reinforcement_Learning
author: Pararth Shah, Marek Fiser, Aleksandra Faust, J. Chase Kew, Dilek Hakkani-Tur
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding and following directions provided by humans can enable robots to navigate effectively in unknown situations. We present FollowNet, an end-to-end differentiable neural architecture for learning multi-modal navigation policies. FollowNet maps natural language instructions as well as visual and depth inputs to locomotion primitives. FollowNet processes instructions using an attention mechanism conditioned on its visual and depth input to focus on the relevant parts of the command while performing the navigation task. Deep reinforcement learning (RL) a sparse reward learns simultaneously the state representation, the attention function, and control policies. We evaluate our agent on a dataset of complex natural language directions that guide the agent through a rich and realistic dataset of simulated homes. We show that the FollowNet agent learns to execute previously unseen instructions described with a similar vocabulary, and successfully navigates along paths not encountered during training. The agent shows 30% improvement over a baseline model without the attention mechanism, with 52% success rate at novel instructions.

##### Abstract (translated by Google)
理解和遵循由人类提供的指导可以使机器人在未知情况下有效导航。我们提供FollowNet，一种用于学习多模式导航策略的端到端可微神经架构。 FollowNet将自然语言指令以及视觉和深度输入映射到运动基元。 FollowNet在执行导航任务时处理使用关注机制的指令，该机制以其视觉和深度输入为条件，集中于命令的相关部分。深度强化学习（RL）稀疏奖励同时学习状态表示，注意功能和控制策略。我们通过复杂的自然语言方向的数据集来评估我们的代理，以指导代理人通过丰富逼真的模拟住宅数据集。我们显示FollowNet代理学会执行之前看不到的类似词汇表的指示，并成功沿着在培训期间未遇到的路径进行导航。与没有注意机制的基线模型相比，代理显示出30％的改善，在新颖的指令下成功率为52％。

##### URL
[http://arxiv.org/abs/1805.06150](http://arxiv.org/abs/1805.06150)

##### PDF
[http://arxiv.org/pdf/1805.06150](http://arxiv.org/pdf/1805.06150)

