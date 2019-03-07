---
layout: post
title: "Training in Task Space to Speed Up and Guide Reinforcement Learning"
date: 2019-03-06 07:39:11
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Guillaume Bellegarda, Katie Byl
mathjax: true
---

* content
{:toc}

##### Abstract
Recent breakthroughs in the reinforcement learning (RL) community have made significant advances towards learning and deploying policies on real world robotic systems. However, even with the current state-of-the-art algorithms and computational resources, these algorithms are still plagued with high sample complexity, and thus long training times, especially for high degree of freedom (DOF) systems. There are also concerns arising from lack of perceived stability or robustness guarantees from emerging policies. This paper aims at mitigating these drawbacks by: (1) modeling a complex, high DOF system with a representative simple one, (2) making explicit use of forward and inverse kinematics without forcing the RL algorithm to "learn" them on its own, and (3) learning locomotion policies in Cartesian space instead of joint space. In this paper these methods are applied to JPL's Robosimian, but can be readily used on any system with a base and end effector(s). These locomotion policies can be produced in just a few minutes, trained on a single laptop. We compare the robustness of the resulting learned policies to those of other control methods. An accompanying video for this paper can be found at https://youtu.be/xDxxSw5ahnc .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02219](http://arxiv.org/abs/1903.02219)

##### PDF
[http://arxiv.org/pdf/1903.02219](http://arxiv.org/pdf/1903.02219)

