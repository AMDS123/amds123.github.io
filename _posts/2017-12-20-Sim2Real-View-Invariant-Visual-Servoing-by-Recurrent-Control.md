---
layout: post
title: "Sim2Real View Invariant Visual Servoing by Recurrent Control"
date: 2017-12-20 18:54:29
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Fereshteh Sadeghi, Alexander Toshev, Eric Jang, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Humans are remarkably proficient at controlling their limbs and tools from a wide range of viewpoints and angles, even in the presence of optical distortions. In robotics, this ability is referred to as visual servoing: moving a tool or end-point to a desired location using primarily visual feedback. In this paper, we study how viewpoint-invariant visual servoing skills can be learned automatically in a robotic manipulation scenario. To this end, we train a deep recurrent controller that can automatically determine which actions move the end-point of a robotic arm to a desired object. The problem that must be solved by this controller is fundamentally ambiguous: under severe variation in viewpoint, it may be impossible to determine the actions in a single feedforward operation. Instead, our visual servoing system must use its memory of past movements to understand how the actions affect the robot motion from the current viewpoint, correcting mistakes and gradually moving closer to the target. This ability is in stark contrast to most visual servoing methods, which either assume known dynamics or require a calibration phase. We show how we can learn this recurrent controller using simulated data and a reinforcement learning objective. We then describe how the resulting model can be transferred to a real-world robot by disentangling perception from control and only adapting the visual layers. The adapted model can servo to previously unseen objects from novel viewpoints on a real-world Kuka IIWA robotic arm. For supplementary videos, see: this https URL

##### Abstract (translated by Google)
即使在出现光学扭曲的情况下，人类也能够从广泛的视角和角度控制他们的肢体和工具。在机器人技术中，这种能力被称为视觉伺服：主要使用视觉反馈将工具或终点移动到所需的位置。在本文中，我们研究如何在机器人操纵场景中自动学习视点不变的视觉伺服技能。为此，我们培训了一个经常性的控制器，可以自动确定哪些动作将机器人臂的终点移动到所需的对象。这个控制器必须解决的问题基本上是模棱两可的：在观点严重变化的情况下，可能不可能在单个前馈操作中确定动作。相反，我们的视觉伺服系统必须利用过去运动的记忆来理解动作如何影响机器人的运动，纠正错误并逐渐靠近目标。这种能力与大多数视觉伺服方法形成鲜明对比，大多数视觉伺服方法要么假定已知的动力学要么需要校准阶段。我们展示了如何使用模拟数据和强化学习目标来学习这个循环控制器。然后，我们描述如何通过将感知与控制分离并仅适应视觉层来将所得模型转移到真实世界的机器人。经过改造的模型可以在现实世界的Kuka IIWA机器人手臂上伺服以前从未见过的新物体。有关补充视频，请参阅：https网址

##### URL
[https://arxiv.org/abs/1712.07642](https://arxiv.org/abs/1712.07642)

##### PDF
[https://arxiv.org/pdf/1712.07642](https://arxiv.org/pdf/1712.07642)

