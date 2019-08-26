---
layout: post
title: "A Comparison of Action Spaces for Learning Manipulation Tasks"
date: 2019-08-23 04:26:26
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Patrick Varin, Lev Grossman, Scott Kuindersma
mathjax: true
---

* content
{:toc}

##### Abstract
Designing reinforcement learning (RL) problems that can produce delicate and precise manipulation policies requires careful choice of the reward function, state, and action spaces. Much prior work on applying RL to manipulation tasks has defined the action space in terms of direct joint torques or reference positions for a joint-space proportional derivative (PD) controller. In practice, it is often possible to add additional structure by taking advantage of model-based controllers that support both accurate positioning and control of the dynamic response of the manipulator. In this paper, we evaluate how the choice of action space for dynamic manipulation tasks affects the sample complexity as well as the final quality of learned policies. We compare learning performance across three tasks (peg insertion, hammering, and pushing), four action spaces (torque, joint PD, inverse dynamics, and impedance control), and using two modern reinforcement learning algorithms (Proximal Policy Optimization and Soft Actor-Critic). Our results lend support to the hypothesis that learning references for a task-space impedance controller significantly reduces the number of samples needed to achieve good performance across all tasks and algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08659](http://arxiv.org/abs/1908.08659)

##### PDF
[http://arxiv.org/pdf/1908.08659](http://arxiv.org/pdf/1908.08659)

