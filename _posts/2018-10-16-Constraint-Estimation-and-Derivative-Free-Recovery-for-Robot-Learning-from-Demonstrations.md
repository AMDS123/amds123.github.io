---
layout: post
title: "Constraint Estimation and Derivative-Free Recovery for Robot Learning from Demonstrations"
date: 2018-10-16 09:42:57
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Jonathan Lee, Michael Laskey, Roy Fox, Ken Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Learning from human demonstrations can facilitate automation but is risky because the execution of the learned policy might lead to collisions and other failures. Adding explicit constraints to avoid unsafe states is generally not possible when the state representations are complex. Furthermore, enforcing these constraints during execution of the learned policy can be challenging in environments where dynamics are difficult to model such as push mechanics in grasping. In this paper, we propose Derivative-Free Recovery (DFR), a two-phase method for generating robust policies from demonstrations in robotic manipulation tasks where the system comes to rest at each time step. In the first phase, we use support estimation of supervisor demonstrations and treat the support as implicit constraints on states. We also propose a time-varying modification for sequential tasks. In the second phase, we use this support estimate to derive a switching policy that employs the learned policy in the interior of the support and switches to a recovery policy to steer the robot away from the boundary of the support if it drifts too close. We present additional conditions, which linearly bound the difference in state at each time step by the magnitude of control, allowing us to prove that the robot will not violate the constraints using the recovery policy. A simulated pushing task in MuJoCo suggests that DFR can reduce collisions by 83\%. On a physical line tracking task using a da Vinci Surgical Robot and a moving Stewart platform, DFR reduced collisions by 84\%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.10321](http://arxiv.org/abs/1801.10321)

##### PDF
[http://arxiv.org/pdf/1801.10321](http://arxiv.org/pdf/1801.10321)

