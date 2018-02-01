---
layout: post
title: "Derivative-Free Failure Avoidance Control for Manipulation using Learned Support Constraints"
date: 2018-01-31 06:57:58
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Jonathan Lee, Michael Laskey, Roy Fox, Ken Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to accomplish tasks such as driving, grasping or surgery from supervisor demonstrations can be risky when the execution of the learned policy leads to col- lisions and other costly failures. Adding explicit constraints to stay within safe zones is often not possible when the state representations are complex. Furthermore, enforcing these constraints during execution of the learned policy can be difficult in environments where dynamics are not known. In this paper, we propose a two-phase method for safe control from demonstrations in robotic manipulation tasks where changes in state are limited by the magnitude of control applied. In the first phase, we use support estimation of supervisor demonstrations to infer implicit constraints on states in addition to learning a policy directly from the observed controls. We also propose a time-varying modification to the support estimation problem allowing for accurate estimation on sequential tasks. In the second phase, we present a switching policy to prevent the robot from leaving safe regions of the state space during run time using the decision function of the estimated support. The policy switches between the robot's learned policy and a novel failure avoidance policy depending on the distance to the boundary of the support. We prove that inferred constraints are guaranteed to be enforced using this failure avoidance policy if the support is well-estimated. A simulated pushing task suggests that support estimation and failure avoidance control can reduce failures by 87% while sacrificing only 40% of performance. On a line tracking task using a da Vinci Surgical Robot, failure avoidance control reduced failures by 84%.

##### Abstract (translated by Google)
学习如何从监督者的示范中完成诸如驾驶，抓握或者手术等任务可能是有风险的，因为学习策略的执行会导致集体和其他代价高昂的失败。当状态表示复杂时，添加显式约束以保持在安全区域内通常是不可能的。此外，在学习策略的执行期间执行这些约束在动态未知的环境中可能是困难的。在本文中，我们提出了一个两阶段的机器人操作任务中的示范演示安全控制方法，其中状态的变化受到所施加的控制量的限制。在第一阶段，除了直接从观察到的控制中学习政策外，我们还使用监督演示的支持估计来推断对状态的隐式约束。我们还提出了支持估计问题的时变修改，以便对顺序任务进行精确估计。在第二阶段，我们提出了一个切换策略来防止机器人在运行时使用估计支持的决策功能离开状态空间的安全区域。机器人的学习策略和新的故障规避策略之间的切换取决于到支架边界的距离。我们证明，如果支持得到了充分的估计，那么使用这个失败避免策略就可以保证推断的约束被执行。模拟推送任务表明支持度估计和故障避免控制可以将故障减少87％，而牺牲性能只有40％。在使用达芬奇手术机器人进行的线路跟踪任务中，故障避免控制将故障减少了84％。

##### URL
[http://arxiv.org/abs/1801.10321](http://arxiv.org/abs/1801.10321)

##### PDF
[http://arxiv.org/pdf/1801.10321](http://arxiv.org/pdf/1801.10321)

