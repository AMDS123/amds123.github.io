---
layout: post
title: "Towards Blended Reactive Planning and Acting using Behavior Trees"
date: 2018-09-14 16:34:35
categories: arXiv_AI
tags: arXiv_AI
author: Michele Colledanchise, Diogo Almeida, Petter &#xd6;gren
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we show how a planning algorithm can be used to automatically create and update a Behavior Tree (BT), controlling a robot in a dynamic environment. The planning part of the algorithm is based on the idea of back chaining. Starting from a goal condition we iteratively select actions to achieve that goal, and if those actions have unmet preconditions, they are extended with actions to achieve them in the same way. The fact that BTs are inherently modular and reactive makes the proposed solution blend acting and planning in a way that enables the robot to efficiently react to external disturbances. If an external agent undoes an action the robot reexecutes it without re-planning, and if an external agent helps the robot, it skips the corresponding actions, again without replanning. We illustrate our approach in two different robotics scenarios.

##### Abstract (translated by Google)
在本文中，我们将展示如何使用规划算法自动创建和更新行为树（BT），在动态环境中控制机器人。算法的规划部分基于反向链接的思想。从目标条件开始，我们迭代地选择实现该目标的动作，如果这些动作具有未满足的前提条件，则通过动作扩展它们以相同的方式实现它们。 BT本身具有模块化和反应性这一事实使得所提出的解决方案混合起作用和规划，使机器人能够有效地对外部干扰作出反应。如果外部代理撤消操作，则机器人在不重新规划的情况下重新执行该操作，并且如果外部代理帮助机器人，则它会再次跳过相应的操作而不重新计划。我们在两种不同的机器人场景中说明了我们的方法

##### URL
[http://arxiv.org/abs/1611.00230](http://arxiv.org/abs/1611.00230)

##### PDF
[http://arxiv.org/pdf/1611.00230](http://arxiv.org/pdf/1611.00230)

