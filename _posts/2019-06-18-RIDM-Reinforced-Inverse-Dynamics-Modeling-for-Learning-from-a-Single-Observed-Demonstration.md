---
layout: post
title: "RIDM: Reinforced Inverse Dynamics Modeling for Learning from a Single Observed Demonstration"
date: 2019-06-18 04:33:51
categories: arXiv_RO
tags: arXiv_RO Knowledge Reinforcement_Learning
author: Brahma S. Pavse, Faraz Torabi, Josiah P. Hanna, Garrett Warnell, Peter Stone
mathjax: true
---

* content
{:toc}

##### Abstract
Imitation learning has long been an approach to alleviate the tractability issues that arise in reinforcement learning. However, most literature makes several assumptions such as access to the expert's actions, availability of many expert demonstrations, and injection of task-specific domain knowledge into the learning process. We propose reinforced inverse dynamics modeling (RIDM), a method of combining reinforcement learning and imitation from observation (IfO) to perform imitation using a single expert demonstration, with no access to the expert's actions, and with little task-specific domain knowledge. Given only a single set of the expert's raw states, such as joint angles in a robot control task, at each time-step, we learn an inverse dynamics model to produce the necessary low-level actions, such as torques, to transition from one state to the next such that the reward from the environment is maximized. We demonstrate that RIDM outperforms other techniques when we apply the same constraints on the other methods on six domains of the MuJoCo simulator and for two different robot soccer tasks for two experts from the RoboCup 3D simulation league on the SimSpark simulator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07372](http://arxiv.org/abs/1906.07372)

##### PDF
[http://arxiv.org/pdf/1906.07372](http://arxiv.org/pdf/1906.07372)

