---
layout: post
title: "Task Transfer by Preference-Based Cost Learning"
date: 2018-09-17 15:02:41
categories: arXiv_RO
tags: arXiv_RO Adversarial Reinforcement_Learning
author: Mingxuan Jing, Xiaojian Ma, Wenbing Huang, Fuchun Sun, Huaping Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of task transfer in reinforcement learning is to migrate the action policy of an agent to the target task from source task. Given their successes on robotic action planning, current methods mostly rely on two requirements: exactly-relevant expert demonstrations or the explicitly-coded cost function on target task, both of which, however, are inconvenient to obtain in practice. In this paper, we relax these two strong conditions by developing a novel task transfer framework where the expert preference is applied as guidance. In particular, we alternate the following two steps: Firstly, Letting experts apply pre-defined preference rules to select related expert demonstrates for the target task. Secondly, based on selection result, we learn the target cost function and trajectory distribution simultaneously via enhanced Adversarial MaxEnt IRL and generate more trajectories by the learned target distribution for the next preference selection. The theoretical analysis on the distribution learning and convergence of the proposed algorithm is provided. Extensive simulations on several benchmarks have been conducted for further verifying the effectiveness of the proposed method.

##### Abstract (translated by Google)
强化学习中任务转移的目标是将代理的动作策略从源任务迁移到目标任务。鉴于它们在机器人行动计划方面取得的成功，目前的方法主要依赖于两个要求：完全相关的专家演示或目标任务的明确编码的成本函数，但这两者在实践中都不方便获得。在本文中，我们通过开发一个新的任务转移框架来放松这两个强大的条件，其中专家偏好被用作指导。特别是，我们采用以下两个步骤：首先，让专家应用预定义的偏好规则，为目标任务选择相关专家演示。其次，基于选择结果，我们通过增强的对抗性MaxEnt IRL同时学习目标成本函数和轨迹分布，并通过学习的目标分布为下一个偏好选择生成更多轨迹。给出了该算法的分布学习和收敛的理论分析。已经对几个基准进行了广泛的模拟，以进一步验证所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1805.04686](http://arxiv.org/abs/1805.04686)

##### PDF
[http://arxiv.org/pdf/1805.04686](http://arxiv.org/pdf/1805.04686)

