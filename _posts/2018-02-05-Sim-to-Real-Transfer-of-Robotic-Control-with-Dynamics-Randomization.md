---
layout: post
title: "Sim-to-Real Transfer of Robotic Control with Dynamics Randomization"
date: 2018-02-05 01:04:24
categories: arXiv_RO
tags: arXiv_RO
author: Xue Bin Peng, Marcin Andrychowicz, Wojciech Zaremba, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Simulations are attractive environments for training agents as they provide an abundant source of data and alleviate certain safety concerns during the training process. But the behaviours developed by agents in simulation are often specific to the characteristics of the simulator. Due to modeling error, strategies that are successful in simulation may not transfer to their real world counterparts. In this paper, we demonstrate a simple method to bridge this "reality gap". By randomizing the dynamics of the simulator during training, we are able to develop policies that are capable of adapting to very different dynamics, including ones that differ significantly from the dynamics on which the policies were trained. This adaptivity enables the policies to generalize to the dynamics of the real world without any training on the physical system. Our approach is demonstrated on an object pushing task using a robotic arm. Despite being trained exclusively in simulation, our policies are able to maintain a similar level of performance when deployed on a real robot, reliably moving an object to a desired location from random initial configurations. We explore the impact of various design decisions and show that the resulting policies are robust to significant calibration error.

##### Abstract (translated by Google)
模拟对于培训人员来说是有吸引力的环境，因为他们提供了丰富的数据来源，减轻了培训过程中的某些安全问题。但是，仿真代理开发的行为往往是特定于仿真器的特性。由于建模错误，在模拟中成功的策略可能不会转移到他们的真实世界的同行。在本文中，我们展示了一个简单的方法来弥合这种“现实差距”。通过随机化训练期间模拟器的动态，我们能够制定能够适应不同动态的策略，其中包括与策略的动态有显着差异的策略。这种适应性使政策能够在没有对物理系统进行任何培训的情况下推广到现实世界的动态。我们的方法在使用机器人手臂的物体推进任务上得到证明。尽管只是在模拟方面进行了培训，但是我们的策略能够在部署在真实机器人上时保持相似的性能水平，从随机初始配置可靠地将对象移动到所需的位置。我们探索各种设计决策的影响，并显示由此产生的策略对于显着的校准误差是稳健的。

##### URL
[http://arxiv.org/abs/1710.06537](http://arxiv.org/abs/1710.06537)

##### PDF
[http://arxiv.org/pdf/1710.06537](http://arxiv.org/pdf/1710.06537)

