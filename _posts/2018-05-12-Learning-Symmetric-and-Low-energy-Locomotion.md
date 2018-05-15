---
layout: post
title: "Learning Symmetric and Low-energy Locomotion"
date: 2018-05-12 14:30:23
categories: arXiv_RO
tags: arXiv_RO Knowledge Reinforcement_Learning
author: Wenhao Yu, Greg Turk, C.Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning locomotion skills is a challenging problem. To generate realistic and smooth locomotion, existing methods use motion capture, finite state machines or morphology-specific knowledge to guide the motion generation algorithms. Deep reinforcement learning (DRL) is a promising approach for the automatic creation of locomotion control. Indeed, a standard benchmark for DRL is to automatically create a running controller for a biped character from a simple reward function. Although several different DRL algorithms can successfully create a running controller, the resulting motions usually look nothing like a real runner. This paper takes a minimalist learning approach to the locomotion problem, without the use of motion examples, finite state machines, or morphology-specific knowledge. We introduce two modifications to the DRL approach that, when used together, produce locomotion behaviors that are symmetric, low-energy, and much closer to that of a real person. First, we introduce a new term to the loss function (not the reward function) that encourages symmetric actions. Second, we introduce a new curriculum learning method that provides modulated physical assistance to help the character with left/right balance and forward movement. The algorithm automatically computes appropriate assistance to the character and gradually relaxes this assistance, so that eventually the character learns to move entirely without help. Because our method does not make use of motion capture data, it can be applied to a variety of character morphologies. We demonstrate locomotion controllers for the lower half of a biped, a full humanoid, a quadruped, and a hexapod. Our results show that learned policies are able to produce symmetric, low-energy gaits. In addition, speed-appropriate gait patterns emerge without any guidance from motion examples or contact planning.

##### Abstract (translated by Google)
学习运动技能是一个具有挑战性的问题。为了产生逼真和平滑的运动，现有的方法使用运动捕捉，有限状态机或形态特定知识来指导运动生成算法。深度强化学习（DRL）是自动生成运动控制的有前途的方法。事实上，DRL的标准基准是通过简单的奖励功能自动为两足动物角色创建一个跑步控制器。虽然几种不同的DRL算法可以成功创建一个运行控制器，但所得到的运动通常看起来并不像一个真正的跑步者。本文采用极简主义学习方法来解决运动问题，而不使用运动例子，有限状态机或形态特定知识。我们介绍了对DRL方法的两种修改，它们一起使用时会产生对称，低能量，更接近真人的运动行为。首先，我们引入鼓励对称行为的损失函数（而不是奖励函数）的新术语。其次，我们引入一种新的课程学习方法，提供调节性的身体帮助，帮助角色左右平衡和向前移动。该算法会自动计算适当的角色援助，并逐渐放松这种援助，以便最终角色学会完全没有帮助地移动。由于我们的方法不使用动作捕捉数据，它可以应用于各种字符形态。我们演示了两足动物，完整人形，四足动物和六足动物的下半部分的运动控制器。我们的研究结果表明，学习政策能够产生对称，低能量的步态。此外，没有任何运动示例或联系计划的指导，速度适当的步态模式就会出现。

##### URL
[http://arxiv.org/abs/1801.08093](http://arxiv.org/abs/1801.08093)

##### PDF
[http://arxiv.org/pdf/1801.08093](http://arxiv.org/pdf/1801.08093)

