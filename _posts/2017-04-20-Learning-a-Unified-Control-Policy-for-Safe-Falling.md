---
layout: post
title: "Learning a Unified Control Policy for Safe Falling"
date: 2017-04-20 15:17:35
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Visak CV Kumar, Sehoon Ha, C Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Being able to fall safely is a necessary motor skill for humanoids performing highly dynamic tasks, such as running and jumping. We propose a new method to learn a policy that minimizes the maximal impulse during the fall. The optimization solves for both a discrete contact planning problem and a continuous optimal control problem. Once trained, the policy can compute the optimal next contacting body part (e.g. left foot, right foot, or hands), contact location and timing, and the required joint actuation. We represent the policy as a mixture of actor-critic neural network, which consists of n control policies and the corresponding value functions. Each pair of actor-critic is associated with one of the n possible contacting body parts. During execution, the policy corresponding to the highest value function will be executed while the associated body part will be the next contact with the ground. With this mixture of actor-critic architecture, the discrete contact sequence planning is solved through the selection of the best critics while the continuous control problem is solved by the optimization of actors. We show that our policy can achieve comparable, sometimes even higher, rewards than a recursive search of the action space using dynamic programming, while enjoying 50 to 400 times of speed gain during online execution.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.02905](https://arxiv.org/abs/1703.02905)

##### PDF
[https://arxiv.org/pdf/1703.02905](https://arxiv.org/pdf/1703.02905)

