---
layout: post
title: "Barrier-Certified Adaptive Reinforcement Learning with Applications to Brushbot Navigation"
date: 2019-08-06 10:43:58
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning Optimization
author: Motoya Ohnishi, Li Wang, Gennaro Notomista, Magnus Egerstedt
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a safe learning framework that employs an adaptive model learning algorithm together with barrier certificates for systems with possibly nonstationary agent dynamics. To extract the dynamic structure of the model, we use a sparse optimization technique. We use the learned model in combination with control barrier certificates which constrain policies (feedback controllers) in order to maintain safety, which refers to avoiding particular undesirable regions of the state space. Under certain conditions, recovery of safety in the sense of Lyapunov stability after violations of safety due to the nonstationarity is guaranteed. In addition, we reformulate an action-value function approximation to make any kernel-based nonlinear function estimation method applicable to our adaptive learning framework. Lastly, solutions to the barrier-certified policy optimization are guaranteed to be globally optimal, ensuring the greedy policy improvement under mild conditions. The resulting framework is validated via simulations of a quadrotor, which has previously been used under stationarity assumptions in the safe learnings literature, and is then tested on a real robot, the brushbot, whose dynamics is unknown, highly complex and nonstationary.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.09627](http://arxiv.org/abs/1801.09627)

##### PDF
[http://arxiv.org/pdf/1801.09627](http://arxiv.org/pdf/1801.09627)

