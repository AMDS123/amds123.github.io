---
layout: post
title: "Interactive Robot Transition Repair With SMT"
date: 2018-02-05 21:52:20
categories: arXiv_RO
tags: arXiv_RO
author: Jarrett Holtz, Arjun Guha, Joydeep Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
Complex robot behaviors are often structured as state machines, where states encapsulate actions and a transition function switches between states. Since transitions depend on physical parameters, when the environment changes, a roboticist has to painstakingly readjust the parameters to work in the new environment. We present interactive SMT-based Robot Transition Repair (SRTR): instead of manually adjusting parameters, we ask the roboticist to identify a few instances where the robot is in a wrong state and what the right state should be. A lightweight automated analysis of the transition function's source code then 1) identifies adjustable parameters, 2) converts the transition function into a system of logical constraints, and 3) formulates the constraints and user-supplied corrections as MaxSMT problem that yields new parameter values. Our evaluation shows that SRTR is effective on real robots and in simulation. We show that SRTR finds new parameters 1) quickly, 2) with only a few corrections, and 3) that the parameters generalize to new scenarios. We also show that a simple state machine corrected by SRTR can out-perform a more complex, expert-tuned state machine in the real world.

##### Abstract (translated by Google)
复杂的机器人行为通常被构造成状态机，其中状态封装动作，并且转换功能在状态之间切换。由于转换取决于物理参数，所以当环境发生变化时，机器人必须精心调整参数才能在新的环境中工作。我们提出了基于交互式SMT的机器人转换修复（SRTR）：我们不是手动调整参数，而是要求机器人识别机器人处于错误状态的几个实例，以及合适的状态。对转换函数的源代码进行轻量级的自动分析，然后1）识别可调整的参数，2）将转换函数转换为逻辑约束系统，3）将约束和用户提供的校正表达为产生新参数值的MaxSMT问题。我们的评估显示，SRTR在真实机器人和仿真中是有效的。我们显示，SRTR快速找到新的参数1），2）只有几个更正，3）参数推广到新的情况。我们还表明，一个由SRTR纠正的简单状态机可以在现实世界中完成一个更复杂的，专家调整的状态机。

##### URL
[http://arxiv.org/abs/1802.01706](http://arxiv.org/abs/1802.01706)

##### PDF
[http://arxiv.org/pdf/1802.01706](http://arxiv.org/pdf/1802.01706)

