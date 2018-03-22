---
layout: post
title: "Learning Robotic Assembly from CAD"
date: 2018-03-20 20:16:18
categories: arXiv_RO
tags: arXiv_RO Knowledge Tracking Reinforcement_Learning
author: Garrett Thomas, Melissa Chien, Aviv Tamar, Juan Aparicio Ojea, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, motivated by recent manufacturing trends, we investigate autonomous robotic assembly. Industrial assembly tasks require contact-rich manipulation skills, which are challenging to acquire using classical control and motion planning approaches. Consequently, robot controllers for assembly domains are presently engineered to solve a particular task, and cannot easily handle variations in the product or environment. Reinforcement learning (RL) is a promising approach for autonomously acquiring robot skills that involve contact-rich dynamics. However, RL relies on random exploration for learning a control policy, which requires many robot executions, and often gets trapped in locally suboptimal solutions. Instead, we posit that prior knowledge, when available, can improve RL performance. We exploit the fact that in modern assembly domains, geometric information about the task is readily available via the CAD design files. We propose to leverage this prior knowledge by guiding RL along a geometric motion plan, calculated using the CAD data. We show that our approach effectively improves over traditional control approaches for tracking the motion plan, and can solve assembly tasks that require high precision, even without accurate state estimation. In addition, we propose a neural network architecture that can learn to track the motion plan, and generalize the assembly controller to changes in the object positions.

##### Abstract (translated by Google)
在这项工作中，受最近制造趋势的驱动，我们研究了自动机器人装配。工业装配任务需要接触丰富的操作技能，这对于使用经典控制和运动规划方法来获取具有挑战性。因此，用于装配领域的机器人控制器目前设计用于解决特定任务，并且不能轻易处理产品或环境中的变化。强化学习（RL）是自主获取涉及接触丰富的动力学的机器人技能的有前途的方法。然而，RL依靠随机探索来学习控制策略，这需要很多机器人执行，并且常常陷入本地次优解决方案中。相反，我们假设先前的知识在可用时可以提高RL的绩效。我们利用这样一个事实，即在现代装配领域中，关于任务的几何信息可以通过CAD设计文件轻松获得。我们建议通过引导RL沿着几何运动计划来利用这些先前的知识，使用CAD数据进行计算。我们表明，我们的方法有效地改进了传统的跟踪运动计划的控制方法，并且可以解决需要高精度的组装任务，即使没有准确的状态估计。另外，我们提出了一种神经网络架构，可以学习跟踪运动计划，并将装配控制器推广到物体位置的变化。

##### URL
[http://arxiv.org/abs/1803.07635](http://arxiv.org/abs/1803.07635)

##### PDF
[http://arxiv.org/pdf/1803.07635](http://arxiv.org/pdf/1803.07635)

