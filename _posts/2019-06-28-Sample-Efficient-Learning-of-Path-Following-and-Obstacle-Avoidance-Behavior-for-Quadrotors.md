---
layout: post
title: "Sample Efficient Learning of Path Following and Obstacle Avoidance Behavior for Quadrotors"
date: 2019-06-28 08:11:27
categories: arXiv_RO
tags: arXiv_RO
author: Stefan Stevsic, Tobias Naegeli, Javier Alonso-Mora, Otmar Hilliges
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an algorithm for the training of neural network control policies for quadrotors. The learned control policy computes control commands directly from sensor inputs and is hence computationally efficient. An imitation learning algorithm produces a policy that reproduces the behavior of a path following control algorithm with collision avoidance. Due to the generalization ability of neural networks, the resulting policy performs local collision avoidance of unseen obstacles while following a global reference path. The algorithm uses a time-free model predictive path-following controller as a supervisor. The controller generates demonstrations by following few example paths. This enables an easy to implement learning algorithm that is robust to errors of the model used in the model predictive controller. The policy is trained on the real quadrotor, which requires collision-free exploration around the example path. An adapted version of the supervisor is used to enable exploration. Thus, the policy can be trained from a relatively small number of examples on the real quadrotor, making the training sample efficient.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12082](http://arxiv.org/abs/1906.12082)

##### PDF
[http://arxiv.org/pdf/1906.12082](http://arxiv.org/pdf/1906.12082)

