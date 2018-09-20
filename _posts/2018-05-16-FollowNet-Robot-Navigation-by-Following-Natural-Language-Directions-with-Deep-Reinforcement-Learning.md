---
layout: post
title: "FollowNet: Robot Navigation by Following Natural Language Directions with Deep Reinforcement Learning"
date: 2018-05-16 06:29:18
categories: arXiv_AI
tags: arXiv_AI Sparse Attention Reinforcement_Learning
author: Pararth Shah, Marek Fiser, Aleksandra Faust, J. Chase Kew, Dilek Hakkani-Tur
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding and following directions provided by humans can enable robots to navigate effectively in unknown situations. We present FollowNet, an end-to-end differentiable neural architecture for learning multi-modal navigation policies. FollowNet maps natural language instructions as well as visual and depth inputs to locomotion primitives. FollowNet processes instructions using an attention mechanism conditioned on its visual and depth input to focus on the relevant parts of the command while performing the navigation task. Deep reinforcement learning (RL) a sparse reward learns simultaneously the state representation, the attention function, and control policies. We evaluate our agent on a dataset of complex natural language directions that guide the agent through a rich and realistic dataset of simulated homes. We show that the FollowNet agent learns to execute previously unseen instructions described with a similar vocabulary, and successfully navigates along paths not encountered during training. The agent shows 30% improvement over a baseline model without the attention mechanism, with 52% success rate at novel instructions.

##### Abstract (translated by Google)
理解并遵循人类提供的指示可以使机器人在未知情况下有效导航。我们介绍了FollowNet，一种用于学习多模态导航策略的端到端可区分神经架构。 FollowNet将自然语言指令以及视觉和深度输入映射到运动原语。 FollowNet处理指令使用注意机制，以其视觉和深度输入为条件，在执行导航任务时专注于命令的相关部分。深度强化学习（RL）稀疏奖励同时学习状态表示，注意功能和控制策略。我们在复杂的自然语言方向数据集上评估我们的代理，通过丰富而真实的模拟家庭数据集来指导代理。我们展示了FollowNet代理学习执行以前看不见的用类似词汇描述的指令，并成功地沿着训练期间未遇到的路径进行导航。在没有注意机制的情况下，该代理比基线模型显示出30％的改善，在新指令中成功率为52％。

##### URL
[http://arxiv.org/abs/1805.06150](http://arxiv.org/abs/1805.06150)

##### PDF
[http://arxiv.org/pdf/1805.06150](http://arxiv.org/pdf/1805.06150)

