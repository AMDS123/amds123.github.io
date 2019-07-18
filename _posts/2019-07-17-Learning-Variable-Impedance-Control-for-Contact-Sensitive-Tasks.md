---
layout: post
title: "Learning Variable Impedance Control for Contact Sensitive Tasks"
date: 2019-07-17 13:20:15
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Miroslav Bogdanovic, Majid Khadiv, Ludovic Righetti
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning algorithms have shown great success in solving different problems ranging from playing video games to robotics. However, they struggle to solve delicate robotic problems, especially those involving contact interactions. Though in principle a policy outputting joint torques should be able to learn these tasks, in practice we see that they have difficulty to robustly solve the problem without any structure in the action space. In this paper, we investigate how the choice of action space can give robust performance in presence of contact uncertainties. We propose to learn a policy that outputs impedance and desired position in joint space as a function of system states without imposing any other structure to the problem. We compare the performance of this approach to torque and position control policies under different contact uncertainties. Extensive simulation results on two different systems, a hopper (floating-base) with intermittent contacts and a manipulator (fixed-base) wiping a table, show that our proposed approach outperforms policies outputting torque or position in terms of both learning rate and robustness to environment uncertainty.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07500](http://arxiv.org/abs/1907.07500)

##### PDF
[http://arxiv.org/pdf/1907.07500](http://arxiv.org/pdf/1907.07500)

