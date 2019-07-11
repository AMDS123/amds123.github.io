---
layout: post
title: "Assessing Transferability from Simulation to Reality for Reinforcement Learning"
date: 2019-07-10 12:56:28
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Fabio Muratore, Michael Gienger, Jan Peters
mathjax: true
---

* content
{:toc}

##### Abstract
Learning robot control policies from physics simulations is of great interest to the robotics community as it may render the learning process faster, cheaper, and safer by alleviating the need for expensive real-world experiments. However, the direct transfer of learned behavior from simulation to reality is a major challenge. Optimizing a policy on a slightly faulty simulator can easily lead to the maximization of the 'Simulation Optimization Bias' (SOB). In this case, the optimizer exploits modeling errors of the simulator such that the resulting behavior can potentially damage the robot. We tackle this challenge by applying domain randomization, i.e., randomizing the parameters of the physics simulations during learning. We propose an algorithm called Simulation-based Policy Optimization with Transferability Assessment (SPOTA) which uses an estimator of the SOB to formulate a stopping criterion for training. The introduced estimator quantifies the over-fitting to the set of domains experienced while training. Our experimental results in two different environments show that the new simulation-based policy search algorithm is able to learn a control policy exclusively from a randomized simulator, which can be applied directly to real system without any additional training on the latter.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04685](http://arxiv.org/abs/1907.04685)

##### PDF
[http://arxiv.org/pdf/1907.04685](http://arxiv.org/pdf/1907.04685)

