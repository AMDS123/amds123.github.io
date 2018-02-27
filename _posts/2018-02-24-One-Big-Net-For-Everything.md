---
layout: post
title: "One Big Net For Everything"
date: 2018-02-24 15:23:46
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Prediction Gradient_Descent
author: Juergen Schmidhuber
mathjax: true
---

* content
{:toc}

##### Abstract
I apply recent work on "learning to think" (2015) and on PowerPlay (2011) to the incremental training of an increasingly general problem solver, continually learning to solve new tasks without forgetting previous skills. The problem solver is a single recurrent neural network (or similar general purpose computer) called ONE. ONE is unusual in the sense that it is trained in various ways, e.g., by black box optimization / reinforcement learning / artificial evolution as well as supervised / unsupervised learning. For example, ONE may learn through neuroevolution to control a robot through environment-changing actions, and learn through unsupervised gradient descent to predict future inputs and vector-valued reward signals as suggested in 1990. User-given tasks can be defined through extra goal-defining input patterns, also proposed in 1990. Suppose ONE has already learned many skills. Now a copy of ONE can be re-trained to learn a new skill, e.g., through neuroevolution without a teacher. Here it may profit from re-using previously learned subroutines, but it may also forget previous skills. Then ONE is retrained in PowerPlay style (2011) on stored input/output traces of (a) ONE's copy executing the new skill and (b) previous instances of ONE whose skills are still considered worth memorizing. Simultaneously, ONE is retrained on old traces (even those of unsuccessful trials) to become a better predictor, without additional expensive interaction with the enviroment. More and more control and prediction skills are thus collapsed into ONE, like in the chunker-automatizer system of the neural history compressor (1991). This forces ONE to relate partially analogous skills (with shared algorithmic information) to each other, creating common subroutines in form of shared subnetworks of ONE, to greatly speed up subsequent learning of additional, novel but algorithmically related skills.

##### Abstract (translated by Google)
我将最近的“学习思考”（2015）和PowerPlay（2011）的工作应用于日益普遍的问题解决者的渐进式培训，不断学习解决新任务而不忘记以前的技能。问题求解器是一个称为ONE的单个循环神经网络（或类似的通用计算机）。从某种意义上说，ONE是不常见的，例如，通过黑匣子优化/强化学习/人工进化以及监督/无监督学习等多种方式进行训练。例如，ONE可以通过神经元进化学习来控制一个机器人，通过改变环境的行为来控制机器人，并且通过无监督的梯度下降来学习，以便如1990年所建议的那样预测未来的输入和向量值的回报信号。用户给定的任务可以通过额外的目标 - 定义输入模式，也是在1990年提出的。假设ONE已经学到了很多技能。现在，可以重新训练ONE的副本以学习新技能，例如通过没有老师的神经进化。在这里它可能会从重复使用以前学过的子程序中获益，但它也可能会忘记以前的技能。然后，ONE以PowerPlay风格（2011年）重新训练（a）执行新技能的ONE副本的输入/输出痕迹和（b）其技能仍被认为值得记忆的先前实例。同时，ONE对旧痕迹（即使是不成功的试验）进行再培训，以成为更好的预测指标，而无需与环境进行额外的昂贵互动。越来越多的控制和预测技能因此被折叠成ONE，就像在神经历史压缩器（1991）的chunker-automatizer系统中一样。这迫使ONE将部分相似的技能（与共享的算法信息）相互关联，以ONE的共享子网的形式创建常见的子程序，以极大地加速随后学习附加的，新颖但算法相关的技能。

##### URL
[http://arxiv.org/abs/1802.08864](http://arxiv.org/abs/1802.08864)

##### PDF
[http://arxiv.org/pdf/1802.08864](http://arxiv.org/pdf/1802.08864)

